<img src="https://storage.googleapis.com/golden-wind/experts-club/capa-github.svg" />

# Deploy de uma aplicação .Net Core em um Azure Web App utilizando Github Actions

Ao final desta aula teremos uma API .Net publicada na Azure usando Aure Web Apps de maneira profissional. Apresentado por [Wilson Neto][1].

## Executar a aplicação

1. Basta baixar usando <br />`git clone https://github.com/rocketseat-experts-club/azure-publishing-dotnet-api-webapp-2021-10-23`
3. Com o Visual Studio 2019 instalado, basta abrir a solution do projeto e apertar F5

## Sobre a Aula

Nesta aula vou te mostrar o passso a passo sobre como públicar aplicações .net na Azure de maneira profissional usando a opção PaaS da Azure, o App Service.

## Link e informações de apoio

- Comando para criação do principal/RBAC:

```
az ad sp create-for-rbac --name "<name>" --role contributor --scopes /subscriptions/<subscription>/resourceGroups/<group> --sdk-auth
```

- Link Código do Pipeline:<br />
https://github.com/rocketseat-experts-club/azure-publishing-dotnet-api-webapp-2021-10-23/blob/main/.github/workflows/deployment-staging.yml

- Link Azure:<br />
https://portal.azure.com/

## Expert

| [<img src="https://github.com/wilsonneto-dev.png" width="75px;"/>][1] |
| :-: |
|[Creator][1]|


[1]: https://www.twitch.tv/wilsonnetodev
