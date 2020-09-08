# Github Explorer
Um projeto front-end feito com ReactJS para consumir dados da API Guihub. :smiley_cat:

<img src="./readmeAssets/github-explorer.gif">


Esta aplicação consome os dados da API do github para buscar qualquer repositório publico disponível na plataforma. É possível também visualizar o número de stars, issues abertas e forks dos repositórios como também detalhes sobre as issues em questão.

## Instalação

Após clonar o repositório, será necessário baixar as dependências do projeto. Para isso, basta abrir o terminal na pasta do projeto e executar o comando abaixo:

```bash
npm install
```

## Execução

Para executar o projeto na sua máquina local, basta abrir o terminal na pasta do projeto e executar o comando abaixo:

```bash
npm start
```
## Detalhes técnicos

- projeto criado a partir do builder **create-react-app** versão 3.4.0;
- O **LocalStorage** é utilizado para armazenar os repositórios pesquisados na aplicação;
- É utilizada a biblioteca **Axios** para realizar as requisições para a API Github;
- Componentes criados a partir do **styled-components**;
