# ![Logo](https://github.com/Math-rm1/sds1/blob/master/front-web/src/assets/logo.svg) Big Game Survey
Big Game Survey é uma aplicação web full-stack construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

## :earth_americas: Hospedagem da aplicação

[![Netlify Status](https://api.netlify.com/api/v1/badges/92d6771c-a8c6-4a73-bc3b-efe5f827bc59/deploy-status)](https://app.netlify.com/sites/math-rm/deploys)

https://math-rm.netlify.app

> Obs.: Durante a primeira execução, os produtos podem demorar alguns segundos para carregar devido ao tempo de inatividade do servidor Heroku.

## :book: Sobre o projeto

O sistema projeta dados extraídos de uma pesquisa de preferência de jogo do público, listando-os e também apresentando-os por meio de um painel gráfico.

### :computer: Layout web
![Web 1](https://github.com/acenelio/assets/raw/main/sds1/web1.png)

![Web 2](https://github.com/acenelio/assets/raw/main/sds1/web2.png)

### :diamond_shape_with_a_dot_inside: Modelo conceitual
![Modelo Conceitual](https://github.com/acenelio/assets/raw/main/sds1/modelo-conceitual.png)

## :rocket: Tecnologias utilizadas
### Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
### Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts
### Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

## :wrench: Como executar o projeto

### Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/Math-rm1/sds1

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

### Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/Math-rm1/sds1

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

## :pencil: Licença

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Math-rm1/sds1/blob/master/LICENSE)

Esse projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## :bust_in_silhouette: Autor

[![Matheus](https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-r-mariano)

Matheus Rodrigues Mariano
