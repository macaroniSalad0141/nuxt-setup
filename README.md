# nuxt-setup

node version v16.17.0


# setup手順
## nvm, node準備
https://github.com/nvm-sh/nvm

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.zshrc

nvm install --lts --latest-npm
nvm install 16
nvm use 16
```

## create nuxt-app
yarn create nuxt-app template-app
 
Programming language: TypeScript
UI framework: Vuetify.js
Nuxt.js modules: Axios
Linting tools: ESLint
Testing framework: Jest
Rendering mode: Single Page App
Deployment target: Server
Development tools: jsconfig.json
Continuous integration: None (またはGitHub Actions)