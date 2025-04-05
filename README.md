# Projeto Azure: Configuração de Azure AI Search, AI Services e Data Accounts

## Introdução
Este projeto faz parte do meu curso de Microsoft Azure, onde configurei recursos como Azure AI Search, Azure AI Services e Azure Data Accounts. Este README documenta o passo a passo realizado no portal do Azure para criar e configurar esses recursos. O objetivo é compartilhar meu aprendizado e fornecer um guia visual para quem está começando a trabalhar com Azure.

## Passo a Passo

### 1. Criação do Azure AI Search
O primeiro passo foi criar um recurso de **Azure AI Search** para indexar e pesquisar dados de forma eficiente.

- Acessei o portal do Azure e cliquei em "Create a resource".
- Pesquisei por "Azure AI Search" e selecionei a opção para criar um novo recurso.
- Configurei os detalhes básicos, como nome do serviço, localização, grupo de recursos e nível de preços (por exemplo, "Basic").
- Após revisar as configurações, cliquei em "Create".

### 2. Criação do Azure AI Services
Em seguida, criei um recurso de **Azure AI Services** para utilizar serviços de inteligência artificial.

- No portal do Azure, cliquei novamente em "Create a resource".
- Pesquisei por "Azure AI Services" e selecionei a opção para criar.
- Preenchi os detalhes, como nome do recurso, localização, grupo de recursos e nível de preços (por exemplo, "S0").
- Aceitei os termos de uso e cliquei em "Create".

### 3. Criação e Configuração do Storage Account
Por fim, criei um **Storage Account** chamado `labprojectdiodecolatech` para armazenar os dados que serão usados pelo Azure AI Search e Azure AI Services.

- **Criação do Storage Account**
  - No portal do Azure, cliquei em "Create a resource" e pesquisei por "Storage Account".
  - Configurei os detalhes básicos, como nome (`labprojectdiodecolatech`), grupo de recursos e localização.
  - Deixei as opções de desempenho e redundância como padrão (Standard e LRS, respectivamente) e cliquei em "Create".
  - 
- **Configuração do Storage Account**
  Ajustei as configurações do Storage Account para permitir o acesso anônimo a blobs, necessário para integração com outros serviços.
  - Na aba "Configuration", habilitei a opção "Allow Blob anonymous access".
  - 
![Anonimous](https://github.com/user-attachments/assets/a8f5e7ca-a924-4aee-bac9-5adae570b9d8)

- **Criação de Containers no Storage Account**
  Após criar o Storage Account, acessei o recurso `labprojectdiodecolatech` e criei um container, anônimo, para armazenar dados: `coffeereviews`.
  
 ![Add-container-anonimous](https://github.com/user-attachments/assets/c5754148-3d6d-422c-a1e2-6edd551ff60f)
 
 - **Visualização Inicial dos Containers**
    Aqui está a tela inicial mostrando o container já criado.
  ![Post-create-container](https://github.com/user-attachments/assets/b83e45e5-ddb1-454f-bf81-320813966bfc)


### 2. Próximos Passos
- Configurar o Azure AI Search para indexar os dados armazenados nos containers.
- Integrar o Azure AI Services para análise de dados.
- Testar a funcionalidade do sistema com os dados armazenados.

## Pré-requisitos
- Uma conta ativa no Microsoft Azure.
- Conhecimento básico sobre o portal do Azure e serviços de armazenamento.
