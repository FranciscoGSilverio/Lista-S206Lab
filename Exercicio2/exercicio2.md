1. Os testes desenvolvidos são manuais ou automatizados?
Os testes desenvolvidos para a API são automatizados pois possuem scripts configurados para verificarem as respostas.

2. Alguns dos testes desenvolvidos são testes Fim-a-Fim (End-To-End)?
Não, todos os testes desenvolvidos são testes de API, ou de integração.

3. O que se deve fazer para que os testes desenvolvidos funcionem em modo regressão?
Testes de regressão verificam se o sistema continua funcionando após alguma alteração, seja adição de alguma funcionalidade ou uma correção. Sendo assim,
para que esses testes funcionem como teste de regressão, basta que as verificações pós-resposta na aba 'scripts' façam as validações de funcionalidades
necessárias, assim, sempre que o código for alterado, basta rodar os testes para a varificação de regressão ser feita.