
# Lista teste de API - S206

O projeto utiliza o postman como ferramenta de criação de testes de API. 



## API utilizada

[JSONPlaceholder](https://jsonplaceholder.typicode.com)


## Uso

Para executar e gerar o relatório de testes, primeiro é necessário ter instalado o pacote newman

```bash
npm install -g newman
```

Caso já tenha instalado, simplesmente execute

```bash
newman run JSONPlaceholder.postman_collection.json -e JSONPlaceholder.postman_environment.json
```

Note que a flag -e indica qual o ambiente deve ser utilizado para rodar os testes. Isso é importante pois a variável de ambiente define a URL base para os endpoints.


