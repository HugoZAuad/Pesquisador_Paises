# Pesquisador de Países

Este projeto é um aplicativo simples que permite aos usuários pesquisar informações sobre países usando a API REST Countries. O aplicativo exibe detalhes como capital, continente, população e a bandeira do país pesquisado.

## Estrutura do Projeto

O projeto é composto por dois arquivos principais:

1. **HTML**: Define a estrutura da página.
2. **JavaScript**: Implementa a lógica de pesquisa e manipulação de dados.

## Funcionalidades

### 1. Pesquisa de Países
- O usuário pode inserir o nome de um país (em inglês) em um campo de entrada.
- Ao clicar no botão "Pesquisar", o aplicativo faz uma requisição à API REST Countries para obter informações sobre o país.

### 2. Exibição de Informações
- Após a pesquisa, o aplicativo exibe as seguintes informações em um cartão:
  - Nome do país
  - Capital
  - Continente
  - População
  - Bandeira do país

## Estrutura HTML

A estrutura HTML é organizada da seguinte forma:

- **Cabeçalho**: Contém o título "Pesquisa de Países".
- **Campo de Entrada**: Um campo de texto para o usuário inserir o nome do país e um botão para iniciar a pesquisa.
- **Cartão de Informações**: Um cartão que exibe os detalhes do país pesquisado, incluindo a bandeira.

## Estilo

O projeto utiliza o framework Bootstrap para estilização, proporcionando uma aparência moderna e responsiva. A classe `bg-dark` é utilizada para um fundo escuro, enquanto o texto é exibido em branco.

## Deploy

- https://pesquisador-paises.vercel.app

## Lógica JavaScript

A lógica do projeto é implementada em um arquivo JavaScript separado. As principais funções incluem:

- **Procurar**: 
  - Lê o valor do campo de entrada.
  - Constrói a URL para a requisição à API REST Countries.
  - Faz a requisição e processa a resposta.
  - Atualiza o cartão com as informações do país, incluindo a bandeira.

## Como Usar

1. Abra o arquivo HTML em um navegador.
2. Insira o nome do país (em inglês) no campo de entrada.
3. Clique no botão "Pesquisar" para buscar informações sobre o país.
4. As informações do país aparecerão no cartão abaixo do campo de entrada.

## Conclusão

Este pesquisador de países é uma aplicação simples, mas eficaz, que demonstra como interagir com APIs e manipular o DOM para exibir informações dinâmicas. É uma boa base para quem deseja aprender mais sobre desenvolvimento web e consumo de APIs.
