# BDS

# Sobre o projeto

BDS é uma API que consiste em um banco de funcionários que podem ser listados e cadastrados pelo usuário logado. Usuários podem ser Administrador (ADMIN) e Operator (OPERATOR). Apenas usuários com o perfil de ADMIN podem cadastrar novos funcionários.

## Layouts da aplicação

![Web_1](https://github.com/LuisPaulo1/assets/blob/master/BDS10/01.jpeg)
#
![Web_2](https://github.com/LuisPaulo1/assets/blob/master/BDS10/02.jpeg)
#
![Web_3](https://github.com/LuisPaulo1/assets/blob/master/BDS10/03.jpeg)
#
![Web_4](https://github.com/LuisPaulo1/assets/blob/master/BDS10/04.jpeg)

## Collection do Postman
Importar o link no Postman: https://www.getpostman.com/collections/940ad90467892e6b1cfb

## Variáveis de ambiente utilizadas no postman
![Postman](https://github.com/LuisPaulo1/assets/blob/master/BDS10/variaveis-ambiente.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/LuisPaulo1/assets/blob/master/BDS10/diagrama-classes.png)

## Usuários para Login
- Email: bob@gmail.com - Senha: 123456 - Perfil: ADMIN
- Email: ana@gmail.com - Senha: 123456 - Perfil: OPERATOR

# Tecnologias utilizadas
## Backend
- Java
- Spring (boot, web, data, security)
- JPA / Hibernate
- Maven
- Banco de dados H2
- JUnit 5

## Frontend
- HTML / CSS / JS / TypeScript
- ReactJS
- React Router DOM
- Axios
- React Hook Form
- QS (Query String)
- JWT Decode
- React Paginate
- React Select
- React Toastify

# Como executar o projeto

## Clonar o repositório
```bash
git clone https://github.com/LuisPaulo1/bds10.git
```

## Para executar o backend
Pré-requisitos: Java 8+

```bash
# entrar na pasta do projeto backend
cd bds10/backend

# executar o projeto
mvn spring-boot:run
```

## Para executar o frontend
Pré-requisitos: yarn

```bash
# entrar na pasta do projeto frontend
cd bds10/frontend

# instalar dependências
yarn

# executar o projeto
yarn start
```
