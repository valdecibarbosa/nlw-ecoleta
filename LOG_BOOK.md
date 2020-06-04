# Diário de Bordo.

## Backend

- Criando aplicação BackEnd:

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


- Instalando os módulos iniciais:

`
npm install express
`

`
npm install typescript @types/express -D
`

`
npm install ts-node-dev -D
`

- inicializar arquivo de configuração typescript na aplicação:

` 
npx tsc --init
`

- Anotações sobre rotas

//rota = endereço completo
//recurso = qual entidade estamos acessando 
//Request Param = parametros que vem na propria rota e identifica um recurso
//Query Param = parametros que vem na propria rota, geralmente opcionais para filtros, paginação, etc ...
//Request Body = parametos para criação e atualização de informações

- Convensões de Rotas

index, show, create, update, delete

- Run knex migrations

`
npx knex --knexfile knexfile.ts migrate:latest
`


## Frontend

- Criando aplicação frontEnd:

`
npx create-react-app web --template=typescript
`

//sempre que criarmos estados com array e objetos é preciso
//informar manualmente os tipos de variaveis usando interface (substituido o PropTypes antigo)