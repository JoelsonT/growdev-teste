
instalar node (apenas 1x)
intalar yarn (apenas 1x)

===> INICIANDO O PROJETO
yarn init -y
yarn add typescript -D
yarn tsc --init

===>ALTERANDO O tsconfig.json
    "target": "ES2020"
    "OutDir": "./dist"
    "rootDir": "./src"

>>> Criar a pasta "src"

===> RODANDO O PROJETO
"npx tsc"
"node ./dist/index"

>>> Download Insomnia

yarn add @types/node -D
yarn add @types/typescript -D
yarn add @types/cors -D
yarn add @types/express -D

yarn add ts-node-dev -D   //Usa quando esta desenvolvendo, serve para agilizar o desenvolvimento.

yarn add express



// Faz o typescript rodar 
// package.json
 },

  "scripts":{
    "dev": "ts-node-dev --respawn --transpile-only ./src/index.ts",
    "build": "tsc",
    "start": "node ./list"
  }

  usar os 3 pontos ... seria o Rest
  const {nome, ...resto} = pessoa;


  /////Exportar 
  const nome = 'Joelson';

function calcular(){
    return 1+1;
}

class Pessoa{

};

export{nome, calcular, Pessoa};

export default calcular; //default seria o mais importante do dados a serem exportados


import { nome,calcular } from "./teste";

import {nome as nomeImportado} from "./teste";

import * as teste from "./teste"

yarn add express

yarn add cors