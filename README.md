# Projeto - estudo de REST API com Spring Boot

## Bootcamp Code Anywhere

### [🔗 Digital Innovation One Inc.🚀](https://web.digitalinnovation.one)

*"Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot"*

Bifurcado de [rpeleias](https://github.com/rpeleias/personapi_digital_innovation_one) - instruções em *[HELP.md](https://github.com/NeiTDutra/dio-restApi-managePeople/blob/main/HELP.md)*

## Tecnologias

[![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?&style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?&style=for-the-badge&logo=intellij-idea&logoColor=white)](https://www.jetbrains.com/pt-br/idea/)
[![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white)](https://www.heroku.com)
[![Java](https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white)](https://www.java.com/pt-BR/)
[![H2*db](https://img.shields.io/badge/H2-H2%20DATA%20BASE%20ENGINE-blue?style=for-the-badge)](https://www.h2database.com/html/main.html)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white)](https://github.com/)


*Tanks for badges from [Ileriayo](https://github.com/Ileriayo/markdown-badges)*

## Recursos

### 📌 Implantação (deploy)

- Implantado no Heroku
- On line [aqui neste link](https://manage-people-api.herokuapp.com/api/v1/people)
- Como é um serviço rest api a resposta é em formato json

### 📌 Formato json

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

### 📌 End points

*De acordo com os verbos http*

- POST = "/api/v1/people" (Adiciona um objeto)
- GET = "/api/v1/people" (Retorna todos objetos)
- GET = "/api/v1/people/id" (Retorna um objeto)
- PUT = "/api/v1/people/id" (Modifica um objeto)
- DELETE = "/api/v1/people/id" (Remove um objeto)

### 📌 Banco de  dados

- [H2 Data Base Engine](https://www.h2database.com/html/main.html)

>
>Welcome to H2, the Java SQL database. The main features of H2 are:
>
>- Very fast, open source, JDBC API
>- Embedded and server modes; in-memory databases
>- Browser based Console application
>- Small footprint: around 2 MB jar file size
>

## 🚧 Recursos em desenvolvimento 🚧

### Novos recursos

- [x] Cadastro de pessoas
- [ ] Adição de endereço para pessoas

(em desenvolvimento...)
