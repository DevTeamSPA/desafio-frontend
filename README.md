<center><div><img src="https://avatars.githubusercontent.com/u/91892865?s=200&v=4" /></div></center>

## Seja Bem-Vindo à SPA!
Estamos felizes de ter você no nosso processo seletivo para Equipe de Desenvolvimento.

Nesse processo, vamos analisar seu conhecimento sobre Frontend e API REST.

### Como enviar

Crie um repositório público no [GitHub](https://github.com). Assim que finalizar seu desafio, envie o link do repositório para o endereço de email `code@spa-br.com`

Lembre-se que estamos analisando seu conhecimento Git também, então utilize [Commits Semânticos](https://blog.geekhunter.com.br/o-que-e-commit-e-como-usar-commits-semanticos/) no processo de desenvolvimento do desafio.

### Dúvidas sobre o desafio

Caso tenha alguma dúvida sobre o desafio, abra uma [issue](https://github.com/DevTeamSPA/desafio-frontend/issues) neste repositório e alguém da nossa equipe de desenvolvimento vai te ajudar! Utilizamos as issues para que cada dúvida possa servir de ajuda para o próximo!

~~~
Você tem 5 dias para entregar o teste!
~~~

A seguir, está seu desafio, boa sorte!

## Desafio

Seu objetivo é criar uma jornada simples de cadastro de usuário utilizando [Next](https://nextjs.org/) e [React](https://reactjs.org/), seguindo o layout. É obrigatório o uso de algum framework de estilo, que trabalhe com o conceito css-in-js. Você também pode instalar alguma outra lib, caso entenda que faça sentido.

## Layout

[Layout](https://www.figma.com/file/eZlPMp5wxk6A90MibytPvQ/Teste-t%C3%A9cnico-SPA?node-id=0%3A1), iremos analisar como você reutiliza código e resolve os desafios.

## Sobre a API

Temos duas rotas de uma API de usuário para que você possa desenvolver a aplicação

~~~
https://636ba0c77f47ef51e135dab3.mockapi.io/api/desafio/
~~~

### Criar usuário

~~~
POST /users
{
  "firstName": String,
  "lastName": String,
  "email": String,
  "password": String,
  "country": String,
  "dateOfBirthday": Date,
  "bio": String,
  "receiveNotifications": Boolean
}
~~~

### Obter dados do usuário

~~~
GET /user/:id
~~~

## O que será avaliado?

* HTML semântico, limpo e claro;
* CSS responsivo, semântico, reutilizável e seguindo boas práticas;
* Tipagem;
* Componentização;
* Conhecimento em javascript;
* Utilização correta do git.

## Bônus

Caso você resolva fazer os seguintes itens, você ganhará um bônus durante a avaliação do seu teste:

* Utilizar [Stitches](https://stitches.dev/)
* Máscara nos campos
* Testes

## Boa sorte!

Atenciosamente, Equipe SPA