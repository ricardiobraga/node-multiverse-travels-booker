# TRAVELS BOOKER

## DESCRIÇÃO
Este é um projeto pessoal inspirado em um desafio técnico para uma vaga de back-end que tive acesso.

### PROJETO ORIGINAL
No projeto original a proposta é uma API feita na linguagem Crystal para planejamento de viagens no universo de Rick and Morty. Uma API um apenas um recurso (/travel-plans), que representa um plano de viagem de forma que cada elemento do array travel_stops é o ID de uma localização na Rick and Morty API.

### ADAPTAÇÃO DO PROJETO
Nessa adaptação estou utilizando Node.js, Express.js e Typescript para criação da API e implementando um modelo de autenticação para que cada usuário tenha acesso ao seu própio “Travel Booker”.

## ENDPOINTS

## Login
* POST /auth/login
## Registro
* POST /auth/register

## Obtenção de todos os planos de viagem

* GET /travel-plans

## Obtenção de um plano de viagem específico

* GET /travel-plans/{id}

## Atualização de um plano de viagem existente

* PUT /travel-plans/{id}

## Exclusão de um plano de viagem existente

* DELETE /travel-plans/{id}

## Query Parameters (opcionais):  

* expand (boolean - falso por padrão): Quando verdadeiro, o campo de travel_stops é um array de entidades com informações detalhadas sobre cada parada.  




