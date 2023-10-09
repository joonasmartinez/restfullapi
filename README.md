## RESTFul API - NODE.JS
____
Este projetinho criado em node foi uma forma de praticar um pouco sobre a forma de criar API Rest sob a estrutura RestFul. É bem simples, mas bem bacana para praticar.
Abaixo algumas imagens do resultado via Postman.

### GET
Desc: Como você pode observar, todo o trabalho é feito no endpoint <code>http://localhost:8080/api/v1/customer-wallets</code>. Ao executar o GET neste endpoint, percebe-se que nada é retornado (No projeto deixei alguns dados mockados para vocês).

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/9294d6e7-1c53-4013-9489-2b4e3230c392)

### POST
Desc.: Aqui vamos passar alguns dados pelo body para poder criar um novo registro em memória em nossa aplicação (Em memória porque não colocamos nenhum banco de dados integrado)

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/523cebc5-fe30-4610-b54a-cd5f989a62c2)

##### Ao executar o comando, teremos o retorno:

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/b4c7915c-8a6c-4670-9a17-b897ebfb63ef)

### PUT
Desc.: Aqui podemos realizar uma atualização dos dados em nosso registro através do método PUT. Agora, para poder identificar em qual usuário desejamos realizar a atualização, devemos passar o id do usuário na url. Assim: <code>http://localhost:8080/api/v1/customer-wallets/7ec02549-1675-4095-86fa-8616a2df4c03</code>

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/3a622cd1-a4a2-47e7-9475-0373d2590cf3)

##### E ao executar o comando, terems o resultado:

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/8c4c6ab9-44a2-4908-b969-46415574b232)

### DELETE
Desc.: Podemos também realizar a deleção de um dado específico de nosso registro, seguindo a mesma forma de identificação do método PUT.

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/415a429f-9119-467f-b70b-b6a063ae5041)

##### e ao executar o comando, teremos o resultado:

![image](https://github.com/joonasmartinez/restfullapi/assets/84146200/58d7e62d-bc0f-458e-85fa-24508dfa8465)



