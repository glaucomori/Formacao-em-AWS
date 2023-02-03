# API Python em ambiente AWS

Projeto usado para criar uma estrutra em nuvem AWS com API Gateway, DynamoDB e AWS Lambda.

## Etapas

- Criação de um database no AWS DynamoDB que armazenará os dados da API.
- Criação de um usuário no AWS IAM definindo acessos liberados.
- Criação de policies e roles no AWS IAM para permitir que AWS Lambda consiga interagir com AWS DynamoDB.
- Criação de API através da AWS API Gateway do tipo REST API.
- Criar os métodos e recursos da API.
- Criar as funções com AWS Lambda. No caso foram criadas através da linguagem Python e usada a biblioteca boto3 para integração do Python com o DynamoDB.
- Configurar os métodos da API conectando-os com as funções lambda.
- Executar os testes no ambiente da API Gateway.
- Realizar chamadas aos métodos através do Postman para verificar o funcionamento da API.
