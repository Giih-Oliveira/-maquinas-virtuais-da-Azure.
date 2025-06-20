# -maquinas-virtuais-da-Azure.

## 📌 Descrição
Este repositório foi criado com o objetivo de documentar a experiência prática utilizando **Máquinas Virtuais (VMs) na plataforma Microsoft Azure**. A proposta faz parte de um trabalho acadêmico voltado para o estudo de computação em nuvem e infraestrutura como serviço (IaaS).

## 🚀 O que são Máquinas Virtuais?
Máquinas Virtuais (VMs) são ambientes computacionais simulados que funcionam como um computador físico, executando sistemas operacionais e aplicações. No Azure, as VMs fazem parte dos serviços de nuvem classificados como IaaS, permitindo criar, configurar, acessar e gerenciar servidores virtuais sob demanda.

## 🏗️ Etapas Realizadas

1. **Criação da Conta no Azure**
   - Cadastro no site do Azure
   - Ativação do crédito gratuito para estudantes (Azure for Students)

2. **Configuração da Máquina Virtual**
   - Escolha da região
   - Seleção da imagem (ex.: Windows Server, Ubuntu, etc.)
   - Definição do tamanho (quantidade de vCPUs, memória RAM)
   - Configuração de usuário, senha e portas (RDP, SSH)

3. **Implantação da VM**
   - Inicialização do serviço
   - Acesso remoto (via Remote Desktop ou SSH)

4. **Testes e Operações**
   - Instalação de programas
   - Execução de comandos
   - Teste de rede e conectividade

5. **Encerramento**
   - Parada da VM para evitar cobranças
   - Exclusão de recursos após uso

## 🔧 Tecnologias Utilizadas
- ☁️ Microsoft Azure
- 🖥️ Windows Server 2022 
- 🔒 Protocolo RDP ou SSH
- 🌐 Gerenciamento via Portal Azure (web)

## 📚 Objetivo Acadêmico
Este projeto visa compreender:
- Conceitos de computação em nuvem
- Gerenciamento de infraestrutura como serviço (IaaS)
- Provisionamento, configuração e manutenção de VMs no Azure

## ✅ Status
Concluído ✔️

## 🧠 Aprendizado
- Criação de recursos na nuvem
- Gerenciamento de redes e segurança (grupos de segurança de rede)
- Noções de escalabilidade e boas práticas no uso de serviços em nuvem

## 📜 Licença
Este projeto é de caráter educacional e não possui fins comerciais.# Relato de Experiência — Utilizando Máquinas Virtuais na Azure

## 🎯 Objetivo
O objetivo deste relato é compartilhar minha experiência prática no uso de uma Máquina Virtual (VM) na plataforma **Microsoft Azure**, como parte de um trabalho acadêmico sobre computação em nuvem.

## 🚀 Início da Jornada
Iniciei criando uma conta no Azure. O processo foi simples, principalmente utilizando a opção de cadastro para estudantes, que oferece crédito gratuito para testes.

## 🔧 Processo de Criação da VM
Durante a criação da máquina virtual, passei pelas seguintes etapas:
- Escolher a **região** mais próxima para menor latência.
- Definir o **sistema operacional**, onde optei por uma distribuição Ubuntu (ou Windows Server, dependendo do teste).
- Configurar a **capacidade da VM**, selecionando uma opção com recursos suficientes para o trabalho, considerando custo e desempenho.
- Criar um **usuário administrativo** e definir as regras de acesso remoto via SSH (para Linux) ou RDP (para Windows).

## 🌐 Desafios Enfrentados
- No início, tive dificuldade para entender as configurações de **grupos de segurança de rede (NSG)**, que controlam quais portas estão abertas na VM.
- A conexão via SSH apresentou dificuldades até que eu percebi que era necessário liberar a porta 22 no firewall da VM.

## 💡 Aprendizados
- Entendi na prática como funciona o provisionamento de servidores na nuvem.
- Aprendi a importância de gerenciar os custos, desligando ou excluindo recursos quando não estão em uso.
- Compreendi melhor conceitos como IP público, portas de entrada, firewall, e escalabilidade.

## 🏁 Encerramento
Após realizar os testes e validar a funcionalidade da VM, encerrei os recursos para evitar cobranças. A experiência me proporcionou uma visão prática dos serviços de nuvem, além de consolidar o aprendizado teórico.

## ✅ Conclusão
A utilização de uma máquina virtual no Azure foi uma experiência enriquecedora, permitindo compreender os principais conceitos de infraestrutura como serviço (IaaS) e explorar, de forma prática, os recursos oferecidos pela computação em nuvem.
