# Desafio Front-end enContact (2021)

Bem-vindo ao teste para front-end na enContact.

Este repositório contém as regras e diretrizes para executar o desafio de aptidão com Front-end na enContact.

## Escopo

O desafio consiste em utilizar um template fictício como base, e replicar todo o site dentro do projeto React.js existente neste repositório, seguindo as orientações dadas.

## Instruções

Abaixo os passos para que você possa iniciar o desafio:

Primeiramente, acesse o sistema [Figma](https://www.figma.com/), utilizando o link do template a ser replicado:
* https://www.figma.com/file/bXFT6AOInY8VOLfJQAnVFP/enContact-Landingpage?node-id=0%3A1

## O repositório

1. Faça o fork do nosso repositório no Github.
2. Clone do projeto.
3. Instale as dependências do projeto (utilizando o `yarn` ou `npm install`).
4. No arquivo `src/app.tsx` você irá encontrar o esqueleto dessa aplicação, este é seu ponto de partida.
5. Utilize `yarn start` ou `npm start` para inicializar a aplicação.

## O que fazer?

1. Transcrever o template disponibilidado no Figma, para o projeto React.js disponibilizado.
2. Criar uma estrutura visual fluente, que permita funcionar em diversos dispositivos (PC e Celular).
3. Ao clicar no botão "Contact us" localizado no topo do site, apresentar um popup seguindo as regras:
    1. Se o horário estiver entre 09:00 e 18:00, o sistema deve apresentar a mensagem "Bem vindo ao nosso atendimento!"
    2. Se o horário estiver entre 18:01 e 08:59, o sistema deve apresentar a mensagem "Estamos fora do nosso horário de atendimento!"
