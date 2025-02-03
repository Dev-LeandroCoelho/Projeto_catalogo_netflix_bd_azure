# Azure Functions

## Descrição
Este repositório contém exemplos de como implementar uma aplicação Serverless utilizando Azure Functions v3, .NET Core 3 e Azure Storage. Ele demonstra conceitos-chave e boas práticas para a construção de aplicações escaláveis e orientadas a eventos em uma arquitetura serverless.

## Como Executar

### Localmente
1. Crie um arquivo `local.settings.json` na raiz do projeto.
2. Adicione as seguintes connection strings ao arquivo:

```json
{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "<Sua_Connection_String_do_Azure_Storage>",
    "AzureWebJobsDashboard": "<Sua_Connection_String_do_Azure_Storage>"
  }
}
Substitua <Sua_Connection_String_do_Azure_Storage> pela sua connection string do Azure Storage.
```
Como alternativa, você pode publicar o projeto diretamente no Azure para implantação na nuvem.

Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para detalhes.
