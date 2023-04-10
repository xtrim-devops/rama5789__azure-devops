# Links

- https://learn.microsoft.com/en-us/azure/devops/artifacts/get-started-npm?view=azure-devops&tabs=Windows

# Pre-requisites (Windows)

```sh
# Get the Tools

$ npm install -g vsts-npm-auth --registry https://registry.npmjs.com --always-auth false

# Project setup

$ npm run refreshVSToken

> sample-node-npm-app@1.0.0 refreshVSToken
> vsts-npm-auth -config .npmrc
:::
vsts-npm-auth v0.42.1.0
-----------------------
Getting new credentials for source:https://pkgs.dev.azure.com/xtrim-devops-1/xtrim-project-1/_packaging/xtrim-devops-public/npm/registry/, scope:vso.packaging_write vso.drop_write

```
