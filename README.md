# Testes automatizados com Cypress - Básico

👋 Seja bem-vindo(a)!

É muito bom tê-lo(a) aqui. Tenho certeza que você vai adorar este curso. ❤️

## O que você vai aprender

Durante o curso de testes automatizados com Cypress (básico), você vai aprender:

- Como configurar um projeto Cypress do zero
- Como visitar páginas locais e remotas
- Como lidar com os elementos mais comuns encontrados em aplicações web
- Como testar _upload_ de arquivos
- Como realizar as mais diversas verificações de resultados esperados
- Como criar comandos customizados
- Como lidar com links que abrem em outra aba do navegador
- Como rodar testes simulando as dimensões de um dispositivo móvel
- Como resolver os mesmos problemas de diferentes formas, conhecendo a [API do Cypress](https://docs.cypress.io/api/table-of-contents)
- Como executar os testes em um _pipeline_ de integração contínua sempre que mudanças ocorrerem no código da aplicação (ou dos testes)
- Como criar uma documentação mínima para seu projeto de testes automatizados

## Vamos começar?

Vá para a seção [estrutura do curso](./lessons/_course-structure_.md).

___

Este é mais um curso da [**Escola Talking About Testing**](https://udemy.com/user/walmyr).

_________________________________________________________________________________________________________________________________________________________

# cypress-basico-v2

Sample project for the basic course of the Talking About Testing online school.

## Pre-requirements

It is required to have Node.js and npm installed to run this project.

> I used versions `v16.13.2` and `8.3.2` of Node.js and npm, respectively. I suggest you use the same or later versions.

## Installation

Run `npm install` (or `npm i` for the short version) to install the dev dependencies.

## Tests

You can run the tests simulating a desktop or mobile viewport.

### Desktop

Run `npm test` (or `npm t` for the short version) to run the test in headless mode
on a desktop viewport.

Or, run `npm run cy:open` to open Cypress in interactive mode
to run the test in headless mode on a desktop viewport.

### Mobile

Run `npm run test:mobile` to run the test in headless mode
on a mobile viewport.

Or, run `npm run cy:open` to open Cypress in interactive mode
to run the test in headless mode on a desktop mobile.