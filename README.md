# DESAFIO QA BEEDOO
Desafio | Analista de Qualidade de Software Júnior

## Descrição do Projeto

Este repositório contém a solução para o desafio de Analista de Qualidade de Software Júnior do Beedoo. O desafio é composto por duas etapas, envolvendo a análise e criação de cenários e casos de teste para o módulo de curso do Beedoo Challenge.

## Estrutura do Repositório

OBS: Esse repositório quando completo vai seguir a seguinte estrutura de pastas abaixo, estarei subindo todos os arquivos no repositório. Nesse momento esta seguindo somente o que foi solicitado no desafio o README.

- `user_story`: Documento contendo a user story e as decisões tomadas.
- `Casos_de_teste_gherkin.xlsx`: Planilha com todos os cenários e casos de teste escritos em Gherkin.
- `evidencias`: Pasta contendo as evidências dos testes em formato MP4.
- `relatorio_bugs`: Relatório com todos os bugs encontrados, seguindo a metodologia escolhida.


## User Story

### Decisões Tomadas

A user story foi criada com base na análise do módulo de curso disponível no [Beedoo Challenge](https://creative-sherbet-a51eac.netlify.app/). As decisões foram tomadas considerando os requisitos funcionais e não funcionais da aplicação, além de possíveis cenários de erro e vulnerabilidades. A seguir está a user story detalhada:

#### User Story

```gherkin
Como um administrador do sistema,
Eu quero criar, listar e excluir cursos,
Para gerenciar o conteúdo educacional da plataforma Beedoo.
```
A documentação para User Stories você pode encontar aqui [User Stories](https://drive.google.com/drive/folders/1xG3nIw7jvsjrzEVmrBrGvkAvZWS71Iz2?usp=sharing)

## Documentação dos Casos de Teste

A documentação dos cenários e casos de teste escritos em Gherkin está disponível na [Planilha Casos de Testes](https://docs.google.com/spreadsheets/d/13Z1zxclOeIBduUBOtesk435R7pMkNIxj/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true).

## Evidências dos Casos de Testes

As evidências dos testes foram gravadas e estão disponíveis no [Google Drive](https://drive.google.com/drive/folders/1yAXA89U-slsxTWwSi8lU28891uIQed_o?usp=sharing). Mas conforme solicitado os links estão todos na planilha acima.

## Relatório de Bugs

### Metodologia Utilizada
A metodologia escolhida para o relatório de bugs foi o ISTQB, que permite uma descrição detalhada e padronizada dos defeitos encontrados.

#### Bugs Encontrados
 Relatório de Bugs Encontrados: [Especificação de Bugs Encontrados](https://docs.google.com/document/d/1Yt1h2zl0_hIHFaI7VsRscNSp2lTbhchE/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)

## Situações e Resolução de Problemas

### Identificação e Resolução de Vulnerabilidades

  Durante os testes, foram identificadas as seguintes vulnerabilidades:

Vulnerabilidade: <br>
Ao acessar a página do desafio, identifiquei que não há um fluxo de login para que o usuário se identifique antes de acessar a tela de lista de cursos e cadastro. Isso torna o sistema vulnerável a ataques, tanto de hackers quanto de usuários não autorizados. Para melhorar a segurança do sistema, sugiro implementar um fluxo de login que exija a identificação dos usuários.


### Pontos Críticos para Esclarecimentos

  1. Especificação dos campos obrigatórios na criação de cursos.
  2. Comportamento esperado para erros de servidor (exemplo: 404) [Evidência](https://docs.google.com/document/d/1Yfe1PFFBFuoBIsOqK0Ekb2jzv8b-QgXq/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true).
  3. Detalhes sobre permissões de usuário para criar e excluir cursos.


### Avaliação de Erros e Definição de Causas
Para avaliar se um erro foi causado pela nova feature:

  1. Revisar o histórico de mudanças do código.
  2. Analisar os logs de execução.
  3. Realizar testes isolados da feature.


### Links Úteis Para o Projeto Completo:

* [Plano de Teste](https://docs.google.com/document/d/1y2TrruPJ0gcqRCACNyknVng5qJtjzCNH/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)
* [Especificação de Casos de Testes](https://docs.google.com/document/d/1dXwx0atyEY3rTFUD42Vk7a4i7FY3_OSM/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)
* [Relatório de Testes](https://docs.google.com/document/d/1NzUAoDx0n1dgXoc7R5rsYLSPM5QtlkoD/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)
* [Relatório de Bugs](https://docs.google.com/document/d/1Yt1h2zl0_hIHFaI7VsRscNSp2lTbhchE/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)
* [Planilha de Casos de Teste em Gherking](https://docs.google.com/spreadsheets/d/13Z1zxclOeIBduUBOtesk435R7pMkNIxj/edit?usp=sharing&ouid=100523648392933019370&rtpof=true&sd=true)
* [Melhorias Propostas](https://drive.google.com/drive/folders/1zcfBx4G9bXCa1Dp1QZZ5PT8Or9khTnUC?usp=sharing)
