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

