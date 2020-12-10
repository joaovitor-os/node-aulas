# BACKEND

## SE - Criar um novo projeto no nodejs
```
npm init
npm install express mysql body-parser --save
npm install cors jsonwebtoken bcryptjs -save
```

## SE - Clonar projeto
```
npm install
```

## Configurar banco de dados

Abrir arquivo backend/app/configs/db.js e alterar configurações

## Importar banco de dados no XAMPP

* Abrir o XAMPP
* Iniciar Apache e MySQL
* Abrir localhost/phpmyadmin
* Clicar na opção "Import" da navbar
* Escolher o arquivo .sql e importar
* Se atentar para erros de "VISIBLE" - retirar se estiver no .sql

## Rodar projeto Node
```
node NOME_DO_ARQUIVO_DE_ENTRADA.js
```

## Alternativa - instalar nodemon
```
npm install -g nodemon
```

## Alternativa - rodar com nodemon
```
nodemon server.js
```