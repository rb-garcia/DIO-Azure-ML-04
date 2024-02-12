# DIO-Azure-ML-04
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

# Visão geral do processo
## AI Search
- Clicar em "Azure AI services"
- Clicar em "AI Search"
- Clicar em "+ Create"
- Preencher os campos Subscription / Resource Group / Service Name
- No campo Location, selecionar "East US" 
- No campo Pricing tier, selecionar o nível "Basic"
- Clicar em "Review + Create"
- Clicar em "Create"

## Criar um recurso de IA
- Clicar em "Create a resource"
- Clicar em "AI + Machine Learning"
- Clicar em "Azure AI services"P
- Preencher os campos Substription / Resource Group
- No campo Region, selecionar "East US"
- Prencher o campo "Name"
- No campo Pricing tier, selecionar opção "Standard S0"
- No campo By checking this box I acknowledge tha... clicar para selecionar
- Clicar em Review + create
- Clicar em Create

## Criar armazenamento
- Clicar em "Storage accounts"
- Clicar em "+ Create"
- Preencher os campos Subscription / Resource Group / Storage account name
- No campo Region, selecionar "East US"
- No campo Performance, selecione a opção "Standard: Recommended for most scenarios..."
- No campo Redundancy, selecion a opção "Locally-redundant storage (LRS)"
- Clicar em "Review"
- Clicar em "Create"
### Configurando o armazenamento
- No grupo de opções do menu "Settings", clicar em Configuration
- Clicar em "Enabled" na opção "Allow Blob anonymous access"
- Clicar em "Save"

## Criar um container
- Clicar na opção "Containers"
- Clicar no botão "+ Container"
- Preencher o campo Name
- No campo "Anonymous access level", selecionar a opção Container (anonymous read access for containers and blobs)
- Clicar em "Create"
### Importar os arquivos para o container
- Clicar no nome do container na lista de containers
- Clicar em "Upload" para fazer o upload dos arquivos

## Exemplos de busca
- search=*&$count=true
- search=locations:'Chicago'
- search=sentiment:'negative'
