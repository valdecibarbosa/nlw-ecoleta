# Diário de Bordo.

## Backend

#### Criando aplicação BackEnd:

`
mkdir backend
cd backend
npm init -y
`

`
cd backend
`

`
npm init -y
`
#### Criando aplicação BackEnd:

`
npm install express
`

`
npm install typescript @types/express -D
`

`
npm install ts-node-dev -D
`

#### inicializar arquivo de configuração typescript na aplicação

` 
npx tsc --init
`

#### Anotações sobre rotas

rota = endereço completo

recurso = qual entidade estamos acessando 

Request Param = parametros que vem na propria rota e identifica um recurso

Query Param = parametros que vem na propria rota, geralmente opcionais para 
filtros, paginação, etc ...

Request Body = parametos para criação e atualização de informações

#### Convensões de Rotas

index, show, create, update, delete

#### Usando knex para tabalhar com sqlite

- Run knex migrations

`
npx knex --knexfile knexfile.ts migrate:latest
`


## Frontend

#### Criando aplicação frontEnd:

`
npx create-react-app web --template=typescript
`

sempre que criarmos estados com array e objetos é preciso

informar manualmente os tipos de variaveis usando interface (substituido o PropTypes antigo)

## mobile

- Iniciando projeto mobile (usando Expo)

`
npm install -g expo-cli
`

`
expo init mobile
`
* escolher template blank com typescript 
  

#### Instalando fontes do Google no Expo.
  
  `
  expo install @expo-google-fonts/ubuntu @expo-google-fonts/roboto  expo-font
  `

### TODO:

 - Trocar inputText por selectBox na vusca de UF e Cidade usando o react-native-picker-select.

 - passar as os caminhos do servidor para varáveis de ambiente.


## Hospedagem

   - Backend

    -- Heroku (somente para testes e demonstrações)
    -- Digital Ocean (Para aplicações pequenas)
    -- AWS / Google Cloud / Microsoft Azure (Para aplicações maiores)

   - Front End
    
    -- Netlify (Automazido com github para deploys) 
    -- Vercel (muito parecido com o Nettlify)
    -- Amazon S3 / Google Cloud Storage (Projetos Grandes)