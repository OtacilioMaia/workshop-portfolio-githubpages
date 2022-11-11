# Workshop de criação de portfólio com GitHub Pages

## Antes de começar:

Crie uma conta no GitHub em https://github.com/join 

## Criando um repositório

Para começar precisaremos de um `repositório`, o repositório é a casa do nosso projeto, é dentro do repositório onde colocaremos todos os arquivos que precisamos para um projeto de software, e lá, temos todo o histórico de versões. 

Com a magia do git, se precisarmos, podemos voltar para qualquer versão anterior do nosso código dentro desse respositório, basicamente uma máquina do tempo do software. 

Para criar um repositório basta clicar no botão `new` ou `novo` no canto superior esquerdo da sua homepage do GitHub (https://github.com/)

<img width="319" alt="Captura de Tela 2022-11-11 às 18 53 16" src="https://user-images.githubusercontent.com/10578275/201436501-e947332e-b542-48f9-a584-7c1a0baa9897.png">

### Repositório com nome especial

Na página de criação do nosso repositório, podemos ver um campo de texto `Repository name` onde podemos batizar este novo projeto que estamos criando. 

<img width="725" alt="Captura de Tela 2022-11-11 às 18 59 43" src="https://user-images.githubusercontent.com/10578275/201436674-e63a0982-8e42-4a29-9985-8d125517e2ee.png">

Também é possível colocar uma descrição legal sobre esse projeto, que deve servir para que outras pessoas possam entender sobre o que ele se trata. 

Aqui, daremos um nome super especial para o repositório, chamaremos ele de `seuNomeDeUsuário.github.io`, é muito importante lembrar de substituir `seuNomeDeUsuário` pelo seu real nome de usuário do GitHub. Meu usário por exemplo é `OtacilioN` então devo criar meu repositório com o nome `OtacilioN.github.io`.

*Caso você já tenha um repositório criado com esse nome, para seguirmos no workshop, chame esse repositório de portfolio, ou outro nome*

Após escolher um nome pro seu repositório, colocar uma descrição, marque a opção `Add a README.md file`, também deixe o seu repositório como público, afinal, queremos mostrar nosso portfólio ao mundo!

<img width="1440" alt="Captura de Tela 2022-11-11 às 19 10 01" src="https://user-images.githubusercontent.com/10578275/201437757-7ad1232a-0c0a-40b6-b771-1152fdc2db89.png">

Uma vez preenchido tudo, basta clicar no botão `Create Repository`

<img width="724" alt="Captura de Tela 2022-11-11 às 19 10 23" src="https://user-images.githubusercontent.com/10578275/201437796-04d631ea-7b65-43fe-870d-45e41cd5682f.png">

## Temos nosso repositório!

Uma vez criado seu repositório, você deve estar numa tela parecida com essa. 

<img width="1440" alt="Captura de Tela 2022-11-11 às 19 11 56" src="https://user-images.githubusercontent.com/10578275/201438236-f27a6ceb-3884-4b6b-816e-a69e09478372.png">

*Se algo não deu certo, esse é o momento de levantar a mão e pedir ajuda*

Você encontrará um ícone de edição no topo do conteúdo do seu README.md, clique neste ícone.

<img width="48" alt="Captura de Tela 2022-11-11 às 19 16 11" src="https://user-images.githubusercontent.com/10578275/201438485-65d65ff4-91e6-4d43-be1f-c03cc98d5b73.png">

Abrirá uma tela de edição onde começaremos nosso site de portfólio.

<img width="1440" alt="Captura de Tela 2022-11-11 às 19 18 18" src="https://user-images.githubusercontent.com/10578275/201438577-3d0ffe81-317c-48f8-bcf5-7e1662aeede7.png">

## Markdown

Você deve ter notado que este arquivo criado termina com a extensão `.md`, isto porque estamos usando `Markdown` que é uma linguagem de marcação, assim como o `HTML`. 

A diferença é que Markdown é pensado para que o conteúdo seja bem legível por humanos ainda no código fonte, sendo mais simples de criar textos, mas ainda ganhar poder de semântica criando títulos, parágrafos, links, imagens, listas, etc. 

Então agora vamos entender um pouco da sintaxe de Markdown. 

### Sintaxe de Markdown 

| Elemento | Sintaxe Markdown        |
|----------|-------------------------|
| Titulos  | # h1 ## h2 ... ### h6   |
| Negrito  | **Texto negrito**       |
| Itálico  | **Texto itálico**       |
| lista ordenada | 1. Primeiro Item 2. Segundo Item 3. Terceiro Item |
| Lista nao ordenada | - Primeiro Item - Segundo Item - Terceiro Item    |
| Link               | [titulo]\(https://www.exemplo.com)              |
| Imagem   | \![texto alternativo]\(linkimagem.jpg) |

## Vamos começar com um título pro Nosso Site, uma descrição de nós mesmos e uma lista de coisas que estamos estudando

<img width="1201" alt="Captura de Tela 2022-11-11 às 19 41 19" src="https://user-images.githubusercontent.com/10578275/201440520-a1ece4d0-f46d-4f34-89c1-9759487aca35.png">

Uma vez criado nosso conteúdo, iremos fazer nosso "commit", fazer um commit é como salvar seu progesso em um jogo, mas em vez de ser um jogo, é salvo o progresso do seu código. 

Podemos dar um nome ao nosso commit e descrever o que fizemos nele.

<img width="1192" alt="Captura de Tela 2022-11-11 às 19 43 42" src="https://user-images.githubusercontent.com/10578275/201440699-8b0276c0-1fc2-4e73-ae14-a64ea7b12f3a.png">

Uma vez escrito sua mensagem de commit, basta clicar no botão verde `Commit changes`
