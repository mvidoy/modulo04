MODULO04: 1-Configurando estrutura
mkdir modulo04
yarn init -y
yarn add @babel/core @babel/preset-env @babel/preset-react webpack webpack-cli -D
yarn add react react-dom
yarn add babel-loader -D
yarn add webpack-dev-server -D
yarn add style-loader css-loader -D
yarn add file-loader -D
yarn add @babel/plugin-proposal-class-properties -D

1)Criar/configurar no raiz:
-babel.config.js
-webpack.config.js 

2)Criar a pasta src no raiz:
dentro da pasta criar o arquivo os arquivoc:
-index.js (arquivo de entrada da aplicação)
-App.css
-App.js

2)Criar a pasta public no raiz:
dentro da pasta criar o arquivo os arquivoc:
-index.html
obs. O bundle.js é gerado automaticamente pelo React.

3)Insirir no package.json:
"scripts": {
    "build": "webpack --mode production",
    "dev": "webpack-dev-server --mode development"
},



