<!--
## Termos de acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

## Boas vindas ao repositório do projeto de ES6 e Testes Unitários!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Atenção a cada passo, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

---

## Sumário

- [Termos de acordos](#termos-de-acordos)
- [Boas vindas ao repositório do projeto de ES6 e Testes Unitários!](#boas-vindas-ao-repositório-do-projeto-de-es6-e-testes-unitários)
- [Sumário](#sumário)
- [Habilidades](#habilidades)
- [Entregáveis](#entregáveis)
  - [O que será desenvolvido](#o-que-será-desenvolvido)
  - [Desenvolvimento](#desenvolvimento)
  - [Data de entrega](#data-de-entrega)
- [Instruções para entregar seu projeto:](#instruções-para-entregar-seu-projeto)
  - [Antes de começar a desenvolver:](#antes-de-começar-a-desenvolver)
  - [Durante o desenvolvimento](#durante-o-desenvolvimento)
- [Como desenvolver](#como-desenvolver)
  - [ESLint](#eslint)
- [Requisitos do projeto](#requisitos-do-projeto)
  - [1. Implemente a função `average`](#1-implemente-a-função-average)
  - [2. Implemente os casos de teste para a função `numbers`](#2-implemente-os-casos-de-teste-para-a-função-numbers)
  - [3. Implemente a função `vqv`](#3-implemente-a-função-vqv)
  - [4. Implemente os casos de teste para a função `circle`](#4-implemente-os-casos-de-teste-para-a-função-circle)
  - [5. Implemente a função `createStudent`](#5-implemente-a-função-createstudent)
  - [6. Implemente os casos de teste para a função `productDetails`](#6-implemente-os-casos-de-teste-para-a-função-productdetails)
  - [7. Implemente as funções `calculator` e `arrayGenerator`](#7-implemente-as-funções-calculator-e-arraygenerator)
  - [8. Implemente a função `myCounter`](#8-implemente-a-função-mycounter)
  - [9. Implemente os casos de teste para a função `getCharacter`](#9-implemente-os-casos-de-teste-para-a-função-getcharacter)
  - [10. Implemente a função `createMenu`, bem como seus casos de teste](#10-implemente-a-função-createmenu-bem-como-seus-casos-de-teste)
- [Depois de terminar o desenvolvimento (opcional)](#depois-de-terminar-o-desenvolvimento-opcional)
- [Revisando um pull request](#revisando-um-pull-request)
- [Avisos finais](#avisos-finais)

---

## Habilidades

Nesse projeto, você será capaz de:

- Escrever testes unitários para funções utilizando o módulo Jest do NodeJS para verificar o correto funcionamento dessas funções;
- A partir de testes já implementados, escrever funções de forma que elas atendam aos testes propostos;
- Escrever testes e funções utilizando uma abordagem de desenvolvimento orientado a testes.

---

## Entregáveis

Para entregar o seu projeto você deverá criar um Pull Request neste repositório.

Lembre-se que você pode consultar nosso conteúdo sobre
[Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

---

### O que será desenvolvido

Você implementará várias funções para atender aos requisitos propostos e/ou testes unitários para garantir que as implementações das funções estão corretas.

---

### Desenvolvimento

* Nos testes unitários que não estão implementados, vocês verão o comando `fail('Teste vazio!');`. Esse código deve ser removido a partir do momento que vocês começarem a escrever o teste unitário. Ele só existe para fazer o teste falhar. Se o `fail('Teste vazio!');` não estivesse nos blocos em que não há testes unitários implementados ainda, o teste iria passar com sucesso, pois não haveria nada para ser testado dentro.

* Os comandos que você utilizará com mais frequência são:
  * `npm test` _(executa todos os testes presentes na aplicação)_
  * `npm test path/to/file` _(executa apenas os testes presentes no arquivo path/to/file)_
    * Exemplo: `npm test tests/average.spec.js`

---

### Data de entrega

- Projeto individual;
- Será um dia de projeto;
- Data de entrega para avaliação final do projeto: `15/03/2022 14:00`

---

## Instruções para entregar seu projeto:

### Antes de começar a desenvolver:

1. Clone o repositório
  * `git clone git@github.com:tryber/sd-020-a-project-js-unit-tests.git`
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd sd-020-a-project-js-unit-tests`

2. Instale as dependências
  * `npm install`

3. Crie uma branch a partir da branch `master`
  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora crie uma branch para qual você vai submeter os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    * Exemplo: `git checkout -b joaozinho-js-unit-tests`

4. Faça as alterações em, por exemplo, alguma das funções que precisam de implementação. Por exemplo, a `average.js` em `src/`:

```javascript
const average = () => {
  // add your implementation here
}

module.exports = average
```

5. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (deve aparecer listado o arquivo _src/last.js_ em vermelho)
  * Adicione o arquivo alterado ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo _src/last.js_ em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto. VAMOS COM TUDO :rocket:'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

6. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin joaozinho-js-unit-tests`

7. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-020-a-project-js-unit-tests/pulls)
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-020-a-project-js-unit-tests/pulls) e confira que o seu _Pull Request_ está criado

---

### Durante o desenvolvimento

:warning: **PULL REQUESTS COM ISSUES NO LINTER NÃO SERÃO AVALIADAS, ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!**

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  4. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

---

## Como desenvolver

Este repositório contém um _template_ de uma aplicação **NodeJS** (observe a existência do arquivo _package.json_). Após clonar o projeto e instalar as dependências, você não precisará realizar nenhuma configuração adicional. Todos os arquivos estritamente necessários para finalizar o projeto já estão criados, **não** sendo necessária a criação de outros arquivos. Você deverá completar as funções e testes unitários de forma a satisfazer os requisitos listados na seção **Lista de requisitos**.

As funções a serem implementadas estão dentro da pasta `src` e seus respectivos testes estão na pasta `tests`. O nome dos arquivos também seguem uma ordem definida. Basicamente, os arquivos de teste possuem o nome do arquivo alvo (arquivo da funcionalidade) acrescido do nome `.spec.js`.

Existirá um arquivo `src/exemplo.js` que conterá a implementação de uma função e um arquivo `tests/exemplo.spec.js` com os testes unitários referentes à função presente no arquivo `src/exemplo.js`.

Cada função possui um bloco de comentários em suas primeiras linhas explicando qual é o trabalho que a função deve realizar.

Você só deve alterar os arquivos indicados nos requisitos. **Os arquivos que não estão indicados nos requisitos não devem ser alterados, ou sua avaliação poderá ser comprometida.**

Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório. Este _Pull Request_ deverá conter a implementação dos arquivos solicitados abaixo.

⚠️ **É importante que seus arquivos tenham exatamente estes nomes!** Apesar de não ser necessário para ser aprovado no projeto, você pode adicionar outros arquivos se julgar necessário. Qualquer dúvida, procure a Pessoa Instrutora que te acompanha.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://app.betrybe.com/course/calendar/fundamentals) sempre que precisar!

---

### ESLint

Usaremos o [ESLint](https://eslint.org/) para fazer a análise estática do seu código.

Para garantir a qualidade do seu código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento nós utilizamos neste projeto o linter `ESLint`. Para rodar o linter localmente no seu projeto, execute o comando abaixo:

```bash
npm run lint
```

Você pode também instalar o plugin do `ESLint` no `VSCode`, basta ir em extensions e baixar o [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint). Caso tenha alguma dúvida sobre o linter você pode consultar nosso conteúdo sobre [`ESLint`](https://app.betrybe.com/course/real-life-engineer/eslint)

⚠️ **PULL REQUESTS COM ISSUES DE LINTER NÃO SERÃO AVALIADAS. ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!**

---

## Requisitos do projeto

### 1. Implemente a função `average`

A função average recebe um array (tamanho variável) e retorna a média dos valores recebidos. Caso a função receba algum valor não numérico ou um array vazio, o valor `undefined` deve ser retornado. Todos os resultados devem ser arredondados para valores inteiros. Ex: 4,6 vira 5; 1,3 vira 1. O arquivo `average.spec.js` contém os testes para `average` já implementados. Implemente a função no arquivo `src/average.js` de forma que ela atenda aos testes propostos.

**O que será avaliado**

* Será validado se, ao receber um array de números, a função `average` retorna a média de seus valores;
* Será validado se, ao receber um array que contém valores não numéricos, a função `average` retorna `undefined`;
* Será validado se, ao receber um array vazio, a função `average` retorna `undefined`.

---

### 2. Implemente os casos de teste para a função `numbers`

A função `numbers` recebe um array (tamanho variável) e retorna `true` se todos os parâmetros forem do tipo 'number' e `false` caso contrário. Essa função já está implementada no arquivo `src/numbers.js`. Escreva pelo menos quatro testes para essa função para garantir que a implementação de `numbers` está correta.

**O que será avaliado**

* Será validado se no teste da função `numbers`, o retorno da função é `true` quando o array passado por parâmetro contém somente números.

---

### 3. Implemente a função `vqv`

Use template literals para escrever uma função que recebe seu nome e sua idade e retorna o parágrafo descrito abaixo:

```javascript
`Oi, meu nome é Tunico!
Tenho 30 anos,
trabalho na Trybe e mando muito em programação!
#VQV!`
```

Caso a função seja chamada sem nenhum parâmetro, o valor `undefined` deve ser retornado. O arquivo `vqv.spec.js` contém os testes para `vqv` já implementados. Implemente a função no arquivo `src/vqv.js` de forma que ela atenda aos testes propostos.

**O que será avaliado**

* Será validado se `vqv` é uma função;
* Será validado se a função `vqv` retorna dados do tipo string;
* Será validado se a função `vqv` retorna a frase esperada quando passados parâmetros de nome e idade;
* Será validado se a função `vqv`, quando chamada sem parâmetros, retorna `undefined`.

---

### 4. Implemente os casos de teste para a função `circle`

A função `circle` recebe o raio de um círculo e retorna um objeto contendo suas informações (Raio, Área e Circunferência). Se não for especificado um raio, a função retorna `undefined`. Essa função já está implementada no arquivo `src/circle.js`. Escreva pelo menos seis testes para essa função para garantir que a implementação de `circle` está correta.

**O que será avaliado**

* Será validado se no teste da função `circle`, ao receber um raio, o retorno da função é um objeto com as informações corretas (Raio, Área e Circunferência).

---

### 5. Implemente a função `createStudent`

A função `createStudent` recebe como parâmetro um **nome**, e retorna um objeto contendo duas chaves:

1. **name**, contendo o nome passado como parâmetro;
2. **feedback**, contendo uma função que retorna a frase 'Eita pessoa boa!' ao ser chamada.

O arquivo `createStudent.spec.js` contém os testes para `createStudent` já implementados. Implemente a função no arquivo `src/createStudent.js` de forma que ela atenda aos testes propostos.

**O que será avaliado**

* Será validado se a função `createStudent` retorna um objeto que contenha duas chaves: `name`, contendo o nome passado como parâmetro; e `feedback`, contendo uma função que retorna a frase 'Eita pessoa boa!' ao ser chamada.

---

### 6. Implemente os casos de teste para a função `productDetails`

A função `productDetails` recebe duas strings que representam nomes de produtos, e retorna um array contendo dois objetos com os detalhes dos respectivos produtos:

```javascript
productDetails('Alcool gel', 'Máscara');
```

**Retorna:**

```js
[
  {
    name: 'Alcool gel'
    details: {
      productId: 'Alcool gel123'
    }
  },
  {
    name: 'Máscara'
    details: {
      productId: 'Máscara123'
    }
  }
]
```

Essa função já está implementada no arquivo `src/productDetails.js`. Escreva pelo menos cinco testes para essa função no arquivo `tests/productDetails.js` para garantir que a implementação de `productDetails` está correta.

**O que será avaliado**

* Será validado se no teste da função `productDetails`, ao receber duas strings, o retorno da função é um array de objetos e se cada objeto contém os dados necessários.

---

### 7. Implemente as funções `calculator` e `arrayGenerator`

  A função `calculator` recebe dois números inteiros como parâmetro e retorna um objeto com as seguintes chaves:
  - sum;
  - mult;
  - div;
  - sub.

  Para cada chave atribua como valor a operação correspondente à sua chave:
  - `sum:` retorna o resultado da soma dos dois números;
  - `mult:` retorna o resultado da multiplicação dos dois números;
  - `div:` retorna o resultado da divisão dos dois números;
  - `sub:` retorna o resultado da subtração dos dois números.

  Os resultados das divisões devem sempre ser arredondados para baixo.

  Parâmetros:
  - Dois números inteiros.

  Comportamento:
  ```javascript
  calculator(1, 2); // { sum: 3, mult: 2, div: 0, sub: -1 }
  ```

  Já a função `arrayGenerator` converte objetos em arrays, de chaves, valores ou ambos. Ela deve receber dois parâmetros:

  * o primeiro parâmetro deve ser uma string que indica o tipo de conversão;
  * o segundo parâmetro deve ser um objeto semelhante ao que é retornado pela função calculator que você acabou de desenvolver.

  Parâmetros:
  - Uma string que indica o tipo de conversão;
  - Um objeto no formato { sum: 3, mult: 2, div: 0, sub: -1 };

  Comportamento:
  ```javascript
  arrayGenerator('keys', { sum: 3, mult: 2, div: 1, sub: 0 }) // [ 'sum', 'mult', 'div', 'sub' ]
  arrayGenerator('values', { sum: 3, mult: 2, div: 1, sub: 0 }) // [ 3, 2, 1, 0 ]
  arrayGenerator('entries', { sum: 3, mult: 2, div: 1, sub: 0 }) // [ [ 'sum', 3 ], [ 'mult', 2 ], [ 'div', 1 ], [ 'sub', 0 ] ]
  ```
O arquivo `objPlayground.spec.js` contém os testes para `calculator` e `arrayGenerator` já implementados. Implemente as funções no arquivo `src/objPlayground.js` de forma que ela atenda aos testes propostos.

**O que será avaliado**

* Será avaliado se a função `calculator` retorna os valores esperados;
* Será avaliado se a função `arrayGenerator` retorna os valores esperados.

---

### 8. Implemente a função `myCounter`

A função myCounter possui dois loops aninhados que inserem valores dentro de um array. Como podemos perceber, eles vão adicionando valores ao array até sua condição de parada. Corrija a função `myCounter`, sem eliminar nenhum dos loops de repetição, para que a função retorne o array correto. O arquivo `myCounter.spec.js` contém os testes para `myCounter` já implementados. Implemente a função no arquivo `src/myCounter.js` de forma que ela atenda aos testes propostos.

**O que será avaliado**

* Será validado se a função `myCounter` retorna os dados esperados de acordo com o que está implementado no teste.

---

### 9. Implemente os casos de teste para a função `getCharacter`

A função `getCharacter` recebe uma string que representa o nome de um personagem e retorna um objeto contendo seu nome, sua classe e suas frases.

```javascript
getCharacter('Arya');
```

**Retorna:**

```javascript
{
  name: 'Arya Stark',
  class: 'Rogue',
  phrases: ['Not today', 'A girl has no name.']
}
```

Essa função já está implementada no arquivo `src/getCharacter.js`. Escreva pelo menos seis testes para essa função no arquivo `tests/getCharacter.spec.js` para garantir que a implementação de `getCharacter` está correta.

**O que será avaliado**

* Será validado se no teste da função `getCharacter` ao receber uma string, o retorno da função é o esperado - de acordo com a tabela apresentada no arquivo de testes.
* Será validado se no teste da função `getCharacter` ao não receber nenhum parâmetro, o retorno da função é `undefined`.
* Será validado se o teste da função `getCharacter` verifica se o parâmetro é case sensitive.

---

### 10. Implemente a função `createMenu`, bem como seus casos de teste

**Agora prepare-se! Esse último requisito vai te guiar através de um longo e rico processo de desenvolvimento orientado a testes (Test Driven Development, ou TDD). Dará trabalho, mas vale a pena!**

Você é responsável por elaborar o sistema de pedidos de um restaurante. Deve ser possível, através desse sistema, cadastrar um menu. Dado que um menu foi cadastrado, o sistema deve disponibilizar um objeto através do qual se consegue:

* Ler o menu cadastrado;
* Fazer pedidos;
* Verificar o que foi pedido;
* Somar o valor da conta.

A estrutura deste código e deste objeto já foi definida e você irá implementá-lo. Você encontrará mais detalhes sobre a estrutura a ser seguida e exemplos do retorno da função no arquivo `src/restaurant.js`. Você deverá seguir o passo-a-passo a seguir para garantir o bom desenvolvimento do sistema.

1. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se a função `createMenu()` retorna um objeto que possui a chave `fetchMenu`, a qual tem como valor uma função.

2. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se `'objetoRetornado.fetchMenu()'` retorna um objeto cujas chaves são somente `food` e `drink`, considerando que a função `createMenu` foi chamada com o objeto: `{ food: {}, drink: {} }`.

3. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se o menu passado pra função `createMenu` é identico ao menu recuperado pela função `'objetoRetornado.fetchMenu()'`.

4. No arquivo `src/restaurant.js`, crie uma função `createMenu()` que, dado um objeto passado por parâmetro, retorna um objeto com o seguinte formato: { fetchMenu: () => objetoPassadoPorParametro }.

5. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se `'objetoRetornado.consumption'`, após a criação do menu, retorna um array vazio.

6. No arquivo `src/restaurant.js`, adicione ao objeto retornado por `createMenu` uma chave `consumption` que, como valor inicial, tem um array vazio.

7. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se ao chamar uma função associada à chave `order` no objeto retornado, passando uma string como parâmetro (como `objetoRetornado.order('coxinha')`), tal string é adicionada ao array retornado em `objetoRetornado.consumption`.

8. No arquivo `src/restaurant.js`, crie uma função, separada da função `createMenu()`, que, dada uma string recebida por parâmetro, adiciona essa string ao array de `objetoRetornado.consumption`. Adicione essa função à chave `order`.

9. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se ao adicionar três pedidos, dentre bebidas e comidas, o array `objetoRetornado.consumption` contém os itens pedidos.

10. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se a função `order` aceita que pedidos repetidos sejam acrescidos a `consumption`.

11. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica que, ao chamar `objetoRetornado.pay()`, retorna-se a soma dos preços de tudo que foi pedido, conforme registrado em `objetoRetornado.consumption`.

12. No arquivo `src/restaurant.js`, adicione ao objeto retornado por `createMenu()` uma chave `pay` com uma função que percorre por todos os itens de `objetoRetornado.consumption`, soma o preço deles e retorna o valor somado acrescido de 10%. DICA: para isso, você precisará percorrer tanto o objeto da chave `food` quanto o objeto da chave `drink`.

**O que será avaliado**

* Será validado se a função `createMenu` retorna os dados esperados.
* Será validado se o teste da função `createMenu` verifica cada um dos retornos da função e se estes retornos têm o comportamento esperado.

---

## Depois de terminar o desenvolvimento (opcional)

Para sinalizar que o seu projeto está pronto para o _"Code Review"_ dos seus colegas, faça o seguinte:

* Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas:
  * No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**;
  * No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**;
  * No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-020-a`.

Caso tenha alguma dúvida, [aqui tem um video explicativo](https://vimeo.com/362189205).

## Revisando um pull request

Use o conteúdo sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os _Pull Requests_.

#VQV

---

## Avisos finais

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o formulário. Leva menos de 3 minutos!

Link: [FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://be-trybe.typeform.com/to/ZTeR4IbH)

O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido. Então, não se assuste se isso acontecer, ok?

-->
