# Software Engineer Guide

Guia para auxiliar desenvolvedores Juniores na jornada de desenvolvimento com foco em Java e Microsserviços. Este guia oferece uma visão geral de conceitos fundamentais, práticas recomendadas e recursos adicionais para impulsionar o aprendizado contínuo.

[![GitHub license](https://img.shields.io/github/license/jjeanjacques10/software-engineer-guide.svg)](https://github.com/jjeanjacques10/software-engineer-guide/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/jjeanjacques10/software-engineer-guide.svg)](https://GitHub.com/jjeanjacques10/software-engineer-guide/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/jjeanjacques10/software-engineer-guide.svg)](https://GitHub.com/jjeanjacques10/software-engineer-guide/issues/)

## Como utilizar

1. Faça um fork do projeto

Clique no botão "Fork" no canto superior direito da página do repositório no GitHub. Isso criará uma cópia do repositório em sua conta.

2. Clone o repositório para o seu ambiente local

``` shell
git clone https://github.com/seu-usuario/software-engineer-guide.git
```

3. Acesse o tópico que deseja estudar e comece a fazer os exercícios dentro das pastas especificadas em cada README. Crie uma nova branch para suas modificações

``` shell
git checkout -b feature/nome-da-sua-feature
```

Substitua **nome-da-sua-feature** por um nome descritivo para a funcionalidade que você está trabalhando.

4. Realize suas modificações e faça commits

``` shell
git add .
git commit -m "Descrição clara das suas alterações"
```

5. Caso tenha algum desenvolvedor com mais sênioridade para lhe guiar abra um novo PR e peça para ele revisar adionando comentários!

    5.1 Abrindo um Pull Request (PR)
    Envie suas modificações para o seu repositório no GitHub

    ``` shell
    git push origin feature/nome-da-sua-feature
    ```

    5.2 Abra um novo Pull Request

    Vá até a página do seu repositório no GitHub e clique no botão "New Pull Request". Descreva suas modificações de forma clara e solicite a revisão de outros desenvolvedores.

## Java POO Fundamentos

Conceitos Básicos

- Classes e Objetos
- Encapsulamento
- Herança
- Polimorfismo
- Abstração

Link para exercícios: [Conceitos Básicos](java-poo/CONCEITOS_BASICOS.md)

## Spring Boot

Objetivo neste módulo é criar uma aplicação do zero utilizando [Spring Boot](https://spring.io/projects/spring-boot). Seguem as introções:

- [API de pessoas](spring-boot/PROJETO_PESSOAS.md): Para aplicar conceitos como RESTful APIs, JPA, e tratamento de exceções.

### Referências

- [Curso Spring Boot - Spring Boot 2 Essentials](https://www.youtube.com/playlist?list=PL62G310vn6nFBIxp6ZwGnm8xMcGE3VA5H)
- [Projeto de referência](https://github.com/jjeanjacques10/springboot-essentials)

## Microsserviços

- Entendimento dos princípios
- Comunicação entre microsserviços
- Escalabilidade e resiliência

### Recomendação de livros

| Title | Autor | Link  |
| ----- | ----- | ----- |
| Migrando sistemas monolíticos para microsserviços| Sam Newman | <https://www.amazon.com.br/Migrando-Sistemas-Monol%C3%ADticos-Para-Microsservi%C3%A7os/dp/6586057043/ref=asc_df_6586057043/?tag=googleshopp00-20&linkCode=df0&hvadid=379739109739&hvpos=&hvnetw=g&hvrand=7666399585960791297&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9100042&hvtargid=pla-902269880868&psc=1> |

## Docker

Docker é uma das ferramentas mais úteis para o desenvolvimento de microsserviços.

- [docker-handbook](https://github.com/jjeanjacques10/docker-handbook)

## Extras

### Código Limpo

Após escrever bastante código algumas dores vão acabar surgindo, seguem alguns materiais que podem lhe ajudar a melhorar o seu código:

| Title | Autor | Link  |
| ----- | ----- | ----- |
| Código limpo: habilidades práticas do Agile software | Robert C. Martion | <https://www.amazon.com.br/C%C3%B3digo-limpo-Robert-C-Martin/dp/8576082675/ref=asc_df_8576082675/?tag=googleshopp00-20&linkCode=df0&hvadid=379792215563&hvpos=&hvnetw=g&hvrand=673144445532925245&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1001736&hvtargid=pla-398225630878&psc=1&mcid=2b0fb83a4146383497d27512de9c9086> |

### Algoritmos

| Title | Autor | Link  |
| ----- | ----- | ----- |
| Entendendo Algoritmos: Um Guia Ilustrado Para Programadores e Outros Curiosos | Aditya Y. Bhargava | <https://www.amazon.com.br/Entendendo-Algoritmos-Ilustrado-Programadores-Curiosos/dp/8575225634> |

# Contribuição

Este guia é um recurso em constante evolução. Sinta-se à vontade para contribuir com sugestões, correções ou adicionar novos recursos através de pull requests.
