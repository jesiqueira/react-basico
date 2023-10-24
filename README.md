# Iniciar o projeto básico

yarn init -y

# criar estrura básica de pasta e arquivo para o projeto

- public
  - index.html
- src
  - index.js

# instalar webpack

yarn add webpack webpack-cli webpack-dev-server -D

# instalar o react e react-dom

yarn add react react-dom

# configuar script para executar o servidor

`"scripts": {
    "start": "webpack-dev-server --mode development --open --hot",
    "build": "webpack --mode production"
  },`

# Babel Minimo

## instalar @babel/core.@bebel/preset-react e babel-loader

yarn add @babel/core @babel/preset-react babel-loader -D

# Criar Arquivo WebPack

- webpack.config.js
