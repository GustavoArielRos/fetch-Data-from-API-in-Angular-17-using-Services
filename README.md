# API
## Resumo:
* basicamente eu peguei uma fake api e somente fiz o método get( que pega todas as informações da api)

link da fake api: https://jsonplaceholder.typicode.com/

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/143faa09-1d45-49b6-8097-39433e5ae9c0)

* esse component vai ter os métodos http que vai fazer o fetch(buscar) a API

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/85630c78-06be-4221-8e3e-20bdd658d74e)


* no app.config temos que importar a função do http client para pode usar ele

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/460054a8-b853-4c50-940c-206e6a10a0b7)

* no console agora já aparece as informações que estamos pegando da api

* agora vou colocar para ver todos os posts

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/f4bcc31e-c3ec-43ba-9fc0-01526803d4a2)

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/1c532a52-7a0c-4253-8785-2d9a54514acc)


![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/9c0f4884-2142-463c-9ef5-05d28757cf8b)


* limitar até 10 posts

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/66631aa0-5ea8-4a6d-a1d8-88bc7083d93a)

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/b9ffa08a-cf19-41a6-a9c4-08c1c90974fc)


* agora vamos adicionar o service
* a gente ta usando o service mais como injeção de depedencia , para os códigos nas lógicas do componente não ficarem muito grande

![image](https://github.com/GustavoArielRos/fetch-Data-from-API-in-Angular-17-using-Service/assets/101509337/50e8e0c5-8ba6-47bf-a85a-2612b26fc54e)
