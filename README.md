# 🚀 Projeto: Criação de Grupo de Recursos e Rede Virtual na Azure

## 📚 Descrição
Este projeto faz parte do Desafio de Projeto da DIO, com o objetivo de fixar os conceitos de computação em nuvem utilizando a plataforma Microsoft Azure.  
Nele, aprendemos a criar um **Grupo de Recursos** e uma **Rede Virtual (VNet)**, preparando a estrutura básica para o gerenciamento de serviços na nuvem.

## 🛠️ Tecnologias Utilizadas
- Microsoft Azure Portal
- Serviços Azure:
  - Resource Group
  - Virtual Network (VNet)

## 📋 Passo a Passo Realizado

### 1. Acesso ao Portal Azure
Acesse o [Portal do Azure](https://portal.azure.com/).

### 2. Criação do Grupo de Recursos
- No menu lateral, clique em **"Grupos de Recursos"**.
- Clique em **"+ Criar"**.
- Escolha uma **assinatura** ativa.
- Defina um **nome** para o Grupo de Recursos.
- Escolha uma **região** (por exemplo: Brazil South).
- Clique em **"Revisar e Criar"** → **"Criar"**.

### 3. Criação da Rede Virtual (VNet)
- No menu lateral, clique em **"Rede Virtual"**.
- Clique em **"+ Criar"**.
- Escolha o **Grupo de Recursos** criado anteriormente.
- Defina o **nome da Rede Virtual**.
- Selecione a **região** correspondente ao Grupo de Recursos.
- Configure o **Endereço CIDR** da rede (exemplo: `10.0.0.0/16`).
- Crie uma **sub-rede** (exemplo: `10.0.0.0/24`).
- Clique em **"Revisar e Criar"** → **"Criar"**.

### 4. Validação
- Após a criação, valide se os recursos foram provisionados corretamente no Azure.
- Verifique a hierarquia entre o Grupo de Recursos e a Rede Virtual.

## 🔗 Links Úteis
- [Portal Azure](https://portal.azure.com/)
- [Documentação Oficial Azure - Grupos de Recursos](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal)
- [Documentação Oficial Azure - Redes Virtuais](https://learn.microsoft.com/pt-br/azure/virtual-network/virtual-networks-overview)

## 📦 Organização do Repositório
```bash
📁 projeto-grupo-recurso-vnet
 ├── 📄 README.md
 ├── 📁 imagens
 │    └── criação-grupo-recurso.png
 │    └── criação-rede-virtual.png
 └── 📄 instruções.txt
