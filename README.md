# adelante-web
Projeto frontend da Adelante Cobrança de Condomínios

## Necessário ter os seguintes itens instalados:
- <a href="https://nodejs.org/en/">Node.js e npm</a>
- <a href="https://yarnpkg.com/lang/en/">Sugiro utilizar o Yarn</a>

## Iniciando projeto:

Abra o terminal no diretório do projeto e digite:

#### `npm install` ou `yarn`

Depois disso basta digitar no terminal:

#### `npm run start` ou `yarn start`

Abrir navegador e digitar:

#### `http://localhost:3000`

## Criando o Container do projeto:

Abra o terminal no diretório do projeto e digite:

#### `npm run build` ou `yarn build`

Após construir seu projeto basta digitar no terminal:

#### `docker build . -t {nome que desaja para imagem}`

Após criar a imagem basta criar o container digitando o seguinte comando:

#### docker run -p 8000:80 {nome da imagem gerada}

Abrir navegador e digitar:

#### `http://localhost:8000`
