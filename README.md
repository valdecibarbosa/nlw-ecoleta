# nlw-ecoleta

Next Level Week 01 - RocketSeat.

Projeto: EcoLeta - App Web e Mobile para cadastro e localização de pontos ecológicos para coleta de resíduos e produtos de reciclagem.

  - [Tecnologias](#tecnologias)
  - [Bibliotecas](#bibliotecas)
  - [Como Iniciar](#como-iniciar)
    - [Back-End (Servidor/API)](#back-end-servidorapi)
    - [Front-End](#front-end)
    - [Mobile](#mobile)


## Tecnologias

- NodeJs 
- TypeScript 
- ReactJs
- React Native

## Bibliotecas

  - **Back-End**
    - Express
    - Sqlite
    - knex
    - multer
    - celebrate/Joi

  - **Front-End**
    - react-router-dom
    - axios
    - leaflet (Free map)
    - react-leaflet

 - **Mobile**
    - Expo
    - Typescript
    - react-navigation
    - axios
    - react-native-picker-select
    - react-native-svg
    - react-native-maps
    - expo-font
    - expo-location
    - expo-mail-composer

## Como Iniciar
### Back-End (Servidor/API)  

```
  # acessando a pasta do Back-End
  cd backend

  # instalando as dependências  
  npm install

  # criando as tabelas
  npm run knex:migrate

  # populando as tabelas pre-definidas
  npm run knex:seed
  
  # Rodando o back-end
  npm run dev

```
### Front-End

``` 
# acessando a pasta do Front-End
cd web

# instalando as dependências  
npm install

# Rodando o front-end
npm start
```

### Mobile
 ```
  # acessando a pasta do Mobile
  cd mobile

  # instalando o expo globalmente
  npm install -g expo-cli

  # instalando as dependências  
  npm install

  #rodando o mobile
  npm start
```

Assim que o mobile começar a rodar, o expo irá abrir uma página no localhost:19002. Baixe o Expo no "Play Store" ou "App Store" e escaneio o QR code para usar seu dispositivo ou baixe um emulador se preferir.




