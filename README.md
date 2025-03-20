Construção de uma API de Projeto-Financeiro para fins Academicos

Instalação dos Pacotes:

npm install express --save
npm install body-parser --save
npm install bcrypt
npm install --save sequelize
npm install --save mysql2


OBSERVAÇAO:
Caso ocorra erro de conexão do Sequelize, vá no mySql Workbench e digite esse comando e execute:

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'sua_senha_do_banco'
