MODULO05: 1-Criando projeto do zero
yarn create react-app modulo05
apagar o arquivo README.md
deletar do package.json:
"eslintConfig": {
    "extends": "react-app"
},
Dentro da pasta public:
index.html => apagar os comentários e <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />

Deletar o arquivo c:\public\manifest.json

yarn start

Deletar da pasta src:
-App.css
-App.test.js
-index.css
-logo.svg
-serviceWorker.js

MODULO05: 2-ESLint, Prettier & EditorConfig
Generate.editorconfig
trim_trailing_whitespace = true
insert_final_newline = true
indent_style = lf

yarn add eslint -D
yarn eslint --init
yarn add prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D

MODULO05: 3-Roteamento no React
yarn add react-router-dom

MODULO05: 4-Styled Components
yarn add styled-components

MODULO05: 6-Estilizando página Main
yarn add react-icons

MODULO05: 7-Adicionando repositórios
yarn add axios

MODULO05: 12-Definindo PropTypes
yarn add prop-types
