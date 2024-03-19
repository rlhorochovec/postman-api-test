# postman-api-test
[![postman-api-test](https://github.com/rlhorochovec/postman-api-test/actions/workflows/ci.yml/badge.svg)](https://github.com/rlhorochovec/postman-api-test/actions/workflows/ci.yml)

Projeto de automação de testes de API utilizando Postman integrado ao GitHub Actions.

## Dependências
- newman
- newman-reporter-htmlextra

## Instalação
Instale as dependências com npm

```bash
  npm install -g newman
  npm install -g newman-reporter-htmlextra
```
## Rodando os testes
Para rodar os testes, rode o seguinte comando

```bash
  newman run "postman-api-test.postman_collection.json" -r htmlextra
```

## Relatório dos testes
[Visualizar](https://rlhorochovec.github.io/postman-api-test/)
Execução local: ./newman

## Screenshots
<img src="https://github.com/rlhorochovec/postman-api-test/blob/develop/Screenshots/api.png" width="600" /><br />
<img src="https://github.com/rlhorochovec/postman-api-test/blob/develop/Screenshots/runs.png" width="600" /><br />
<img src="https://github.com/rlhorochovec/postman-api-test/blob/develop/Screenshots/report.png" width="600" /><br />
<img src="https://github.com/rlhorochovec/postman-api-test/blob/develop/Screenshots/newman.png" width="600" />
