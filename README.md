\# QA API Automation - Restful Booker



Projeto de automação de testes de API REST utilizando Postman e Newman.



\## Tecnologias utilizadas



\- Postman

\- Newman

\- Node.js

\- Git/GitHub

\- Restful Booker API



\## Cenários testados



\- Health check da API

\- Criação de token de autenticação

\- Criação de booking

\- Consulta de booking criado

\- Atualização de booking

\- Exclusão de booking

\- Validação de exclusão com retorno 404



\## Como executar



Instale o Newman:



```bash

npm install -g newman

```

Execute a collection:



newman run postman/restful-booker-collection.json

Resultado esperado



A execução deve finalizar com:



7 requests executadas

13 assertions

0 falhas

Objetivo do projeto



Demonstrar conhecimentos em testes de API, validação de endpoints REST, automação com Newman e organização de projeto de QA para portfólio.



Autor



Sergio Velasquez

LinkedIn: https://www.linkedin.com/in/sgsvelasquez/

