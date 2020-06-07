# Ecoleta

## Sobre

O **Ecoleta** é um projeto proposto na **Next Level Week** promovido pela Rocketseat
inspirado na **Semana Internacional do Meio Ambiente**, cujo desafio é construir em uma semana uma aplicação composta de back-end, front-end e mobile utilizando algumas das tecnologias mais inovadoras do mercado.

A funcionalidade do Ecoleta é basicamente fornecer informações sobre pontos de coleta de materiais recicláveis ou descartes tóxicos que não podem ser deixados em lixo comum.

Na interface web, é possível cadastrar seu ponto de coleta, informando nome, contato, localização, e quais itens podem ser recolhidos.

Enquanto que pelo app, um cidadão pode pesquisar por pontos de coleta próximos, filtrando pela cidade e pelo tipo de item que deseja descartar, o resultado é disponibilizado em um mapa, e ao se tocar em um ponto, as informações detalhadas são exibidas em uma tela de onde também é possível entrar em contato com o pessoal via email ou whatsapp.

## Tecnologias utilizadas

- Server
  - [Node.js](https://github.com/nodejs/node)
  - [Express](https://github.com/expressjs/express)
  - [TypeScript](https://github.com/Microsoft/TypeScript)
  - [Knex](https://github.com/knex/knex)
  - [Multer](https://github.com/expressjs/multer)
  - [Joi](https://github.com/hapijs/joi)

- Web
  - [React](https://github.com/facebook/react)
  - [React-Leaflet](https://github.com/PaulLeCam/react-leaflet)

- Mobile
  - [React Native](https://github.com/facebook/react-native)
  - [Expo](https://github.com/expo/expo)
  
- Outras
  - [Feather](https://github.com/feathericons/feather)
  - [Axios](https://github.com/axios/axios)

## Como executar para testes

### Servidor

Com o Node instalado em tua máquina, vá para o diretório do servidor e instale as dependências:
` $ npm install `

Para gerar e pré-popular o banco de dados sqlite execute os seguintes comandos:
` $ npm run knex:migrate`
` $ npm run knex:seed`

O seguinte comando enfim executa o servidor:
` $ npm run dev `

### Web

Por um imprevisto, o front-end web foi mantido com Yarn, neste caso o use para instalar as dependências e executar:
` $ yarn install `
` $ yarn start `

### Mobile

Para executar o front-end mobile, você deve utilizar o Expo. O instale em tua máquina com:
` $ npm install -g expo-cli `

Instale o aplicativo do Expo em teu celular, e use os comandos para gerar o bundle:
` $ expo install `
` $ expo start `

Por fim escaneie o QR code com o aplicativo do Expo.

Ps.: Para conseguir integrar corretamente o app com o servidor, é necessário trocar todos os arquivos onde há "localhost" pelo ip local da tua máquina.

Obrigado pelo teu interesse em meu projeto. ♥

<p align="center"><img src="https://lander.rocketseat.dev/uploads/nextlevelweek_18baaf82af.svg"/></p>
 <h4 align="center">NextLevelWeek 1.0</h4>
 
