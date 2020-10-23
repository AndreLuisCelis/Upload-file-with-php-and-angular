# Upload de Arquivo com php e angular

Implementação de um simples sistema para fazer upload de arquivos através de um  script PHP que disponibiliza o endpoint /upload.php para requisiçoes POST , com CORS habilitado para aceitar requisiçoes de diferentes domínios

Frontend criado com angular 10 ,formulario para  upload utilizando o FormData e HttpClient para enviar os dados para o servidor PHP  através de um formualario reativo vinculado a um <form>

## serve PHP
Para rodar o servidor PHP , na pasta do projeto entre com o seguinte commando 
`php -S localhost:8000`

## Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
