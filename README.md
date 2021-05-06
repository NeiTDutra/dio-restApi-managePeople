# Projeto - estudo de REST API com Spring Boot

## Bootcamp Code Anywhere

### [🔗 Digital Innovation One Inc.🚀](https://web.digitalinnovation.one)

*"Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot"*

Bifurcado de [rpeleias](https://github.com/rpeleias/personapi_digital_innovation_one) - intruções *HELP.md*

## Tecnologias



### Recursos

📌 Implantação (deploy):

- Implantado no Heroku
- On line [aqui neste link](https://manage-people-api.herokuapp.com/api/v1/people)
- Como é um serviço rest api a resposta é em formato json

📌 Formato json:

*Formato de tratamento dos dados*

```json
{
    "firstName": "notNull",
    "lastName": "notNull",
    "cpf": "000.000.000-00 notNull",
    "birthDate": "00-00-0000 null",
    "phones": [
        {
            "type": "HOME || MOBILE || COMMERCIAL notNull",
            "number": "(00)000000000 notNull"
        }
    ]
}
```

📌 End points:

*De acordo com os verbos http*

- POST = "/api/v1/people" (Adiciona um objeto)
- GET = "/api/v1/people" (Retorna todos objetos)
- GET = "/api/v1/people/id" (Retorna um objeto)
- PUT = "/api/v1/people/id" (Modifica um objeto)
- DELETE = "/api/v1/people/id" (Remove um objeto)

📌 Banco de  dados:

- [H2 Data Base Engine](https://www.h2database.com/html/main.html)

>Welcome to H2, the Java SQL database. The main features of H2 are:
>
>- Very fast, open source, JDBC API
>- Embedded and server modes; in-memory databases
>- Browser based Console application
>- Small footprint: around 2 MB jar file size

## 🚧 Recursos em desenvolvimento 🚧

### Novos recursos:

- Adição de endereço para pessoas 

(em desenvolvimento...)
