Verificar se existe o node instalado
node -v
se precisar instalar o curl = sudo apt install curl
ativar o repositório
curl -sL https://deb.nodesource.com/setup 12.x | sudo -E bash -
--instalar o node
sudo apt-get install -y nodejs
verificar a versao do npm
npm -v
--instalar o yarn
sudo npm install yarn -g
yarn -v

-- gerar o editor config
-- iniciar o projeto
yarn init -y
-- adicionar express
yarn add express
-- adicionar o typescript
yarn add typescript -D
-- iniciar o typescript
yarn tsc --init
configurar o tsconfig
-- adicionao ao projeto types
yarn add @types/express -D
--gerar o typescript para javascript
yarn tsc
-- aprendeu como rodar o servidor
node dist/server.js
-- instalar o ts-node-dev
yarn add ts-node-dev -D
--adicionou os scripts build e dev:server no package.json
--adicionei o eslint
yarn add eslint -D
yarn eslint --init
--configurar o vs code
"[javascript]":{

        "editor.codeActionsOnSave": {

        "source.fixAll.eslint": true,

        }

    },

    "[javascriptreact]":{

    "editor.codeActionsOnSave": {

    "source.fixAll.eslint": true,
    }

    },

--adicionar uma importpara o typescript
yarn add -D eslint-import-resolver-typescript

--add o pretier eslint-config-pretier eslint-plugin-pretier -D

--configurei o prettier
criou o arquivo prettier.config.js

--configurei o eslintrc

-- configurei o launch json

PATTERN REPOSITORY/ SERVICE
boilerplate = conjunto de arquivos


