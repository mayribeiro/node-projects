
Install expressjs

npm install express --save-dev

Install Nodemon run server livereload watching
npm install -g nodemon

Install o EJS templates para o servidor
npm install ejs --save-dev

Run
nodemon app.js

.exit sair do terminal node

O que são módulos?
Permitem organizar o código
Isolar uma determinada lógica e permitir sua utilização de forma recorrente dentro de uma aplicação.
Permite também a reutilização dessa lógica em outros projetos.
Possibilidade de distribuir esse módulo na internet para outros desenvolvedores.

O que é o CommonJS?
https://pt.wikipedia.org/wiki/CommonJS

CommonJs é uma API com o objetivo de agrupar as necessidades de
diversas aplicações javascript em uma única API, que funcione em
diversos ambientes e interpretadores. Criando o conceito de se módulos
que façam essas funções. E estes módulos podem ser carregados
assincronamente com ferramentas AMD.

MVC é nada mais que um padrão de arquitetura de software, separando
sua aplicação em 3 camadas. A camada de interação do usuário(view),
a camada de manipulação dos dados(model) e a camada de controle(controller).

Model
Regras de negócio da aplicação e manipulação com o banco de dados.

View
A camada de interação com o usuário.
Ela apenas faz a  exibição dos dados, sendo ela por meio de um html ou xml.

Controller
O responsável por receber todas as requisições do usuário.
Seus métodos chamados actions são responsáveis por uma página,
controlando qual model usar e qual view será mostrado ao usuário.

Mysql:
https://dev.mysql.com/downloads/mysql/

Modulo para Mysql:
npm install mysql --save

Instalar o body-parser:
npm install body-parser --save