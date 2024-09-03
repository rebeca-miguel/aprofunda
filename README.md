## Projeto API com Node.js

# Conceitos aprendidos durante a semana:

## Tema
Design Patern e Boas Práticas.
Entendendo que a aplicação de de padrões em projetos é importante para que a nossa aplicação ainda que extensa, seja ompreensível e dinámica, facilitando não só para o cliente mais também para futuras atualizações.
Entretanto, isso acontece devido a Refatoração da API utilizando design pattern e melhoria de práticas.

## O que é o Design Patterns:
**São soluçoes reutilizaveis para problemas de designe de softwere que surgem repetidamente, ou seja, soluções comprovadas para problemas comuns.

Existem uma grande diferança entre arquitetura e Design de softwere, que são:
Arquterura de Softwere é o conjuto de aplicações dede banco de dados, fluxos de informações e como cada componente do nosso softwere vai acontecer como nosso sistema irá se comunicar.

Design de Softwere, a gente olha de uma forma mais ampla no código e ao invés de olhar para o banco de dados, olhamos para o código da nossa aplicação analisando se de que forma vamos escrever  código e qual fique mais fácil para a leitura. Permitindo modificações ages por parte do time.

Os obejtos são o que podemos construir com essa forma.

Exemplo:
Temos o objeto casa, que será a nossa classe e nela podemos ver quais propriedades teremos.
Atraves de um arquivo casa.js, criamos o seguinte:

class casa {
construtor (quartos, banheiros, sala e cozinha)
Criamos os atributos propriedade da minha casa usabdo o this.quartos = quartos;  this.banheiro = banheiro;  this.sala = sala;  this.cozinha = cozinha;

Sendo assim, com a mesma classe eu posso criar objetos diferentes que fazem sentido para a nossa regra de negócio. Da seguinte forma:
**const minhaCasa = new Casa(4, 5, 2, 1), o Neu é a minha palavra reservada.

## Função e class
Uma função realiza uma tarefa específica, enquanto que uma classe agrupa dados e funcionalidade que pertecem ao mesmo contexto.

** Uma classe permite criar vários objetos, e facilita a expansão e manutenção do código em projetos maiores.

**O conteúdo apresenta três padrões fundamentais a serem implementos para a melhoria do nosso código:
-Factory;
-Strategy;
-Singleton

## Tecnologias Utilizadas
Node.js
Express.js
JavaScript

Para a construção da nossa API, criamos:

> 1 - rotas através dos métodos: GET, POST, PATH OU PUT E DELETE
> 
> router.patch('/posts/:id', updatePost); // PATCH para atualizar parte do recurso
> router.delete('/posts/:id', postsController.deletePost)

Atualizar Postagem

- **URL**: `/posts/:id`
- **Método**: `PATCH` ou `PUT`
- **Descrição**: Atualiza uma postagem específica.
- **Corpo da Requisição**:
  ```json
  {

S![PATH ](https://github.com/user-attachments/assets/d12613ed-5fda-4bd2-837c-d03151ea085d)

Excluir Postagem
- **URL: /posts/:id**
-**Método: DELETE**

  S![PATH ](https://github.com/user-attachments/assets/d12613ed-5fda-4bd2-837c-d03151ea085d)

200 OK: 
e a postagem for atualizada com sucesso.
404 Not Found: Se a postagem com o ID especificado não for encontrada.


Rodando o projeto
-npm start






**Durante a semana3 do curso Aprofunda pretalab, nos foi desafido a farmos a refatoração do projeto API com Node.js
