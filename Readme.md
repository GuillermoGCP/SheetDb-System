## SheetDb System

Sistema base para utilizar hojas de cálculo de Google para almacenar datos, utilizando SheetDb para encapsular la lógica de autentificación y los métodos del módulo para interactuar con las hojas.

Instalación:
npm install sheetdb-node --save
Scripts:
npm run dev, para iniciar en modo desarrollo.
Repositorio: https://github.com/sheetdb/sheetdb-node
Url: https://sheetdb.io/
Stack: Node.js, Javascript, SheetDb, Express, Cors, Dotenv, uuid, Node-fetch

Endpoints:
Method: post, Route:('/activities/create')
Method: patch, Route:('/activities/update')
Method: delete, Route:('/activities/:field/:value')
Method: get, Route:('/activities/:sheetName')
Method: get, Route:('/activities/search/:field/:value')
