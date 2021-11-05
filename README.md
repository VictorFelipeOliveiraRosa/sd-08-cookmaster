## O que foi desenvolvido

Foi desenvolvido um app utilizando a arquitetura MSC!

Neste novo projeto é possível fazer o cadastro e login de pessoas usuárias, onde apenas essas pessoas poderão acessar, modificar e deletar as receitas que cadastrou.

# Técnologias
 - NodeJs;
 - Express;
 - joi;
 - mongodb;
 - multer;
 - nodemon;
 - jest;
 - sinon;
 - eslint;

## instalação
  ```
  npm install
  ```
# Habilidades desenvolvidas e praticadas

- Entender o que há por dentro de um token de autenticação;

- Gerar tokens a partir de informações como login e senha;

- Autenticar rotas do Express, usando o token JWT;

- Fazer upload de arquivos em APIs REST;

- Salvar arquivos no servidor através de uma API REST;

- Consultar arquivos do servidor através de uma api REST.

- Realizar testes de integração

## Desenvolvimento

Eu desenvolvi todas as camadas da aplicação (Models, Service e Controllers).

Através dessa aplicação, será possível realizar as operações básicas: Criação, Leitura, Atualização e Exclusão.

Para realizar qualquer tipo de alteração no banco de dados (como cadastro, edição ou exclusão de receitas) será necessário autenticar-se. Além disso, as pessoas usuárias devem poder ser clientes ou administradores. Pessoas clientes apenas poderão disparar ações nas receitas que ele mesmo criou. Já uma pessoa administradora pode disparar qualquer ação em qualquer receita.

A autenticação deverá ser feita via `JWT`.

O código para cadastro de pessoas usuárias deve ser criado por você utilizando os conhecimentos adquiridos nesse bloco.

Deverá ser possível adicionar uma imagem à uma receita, utilizando o upload de arquivos fornecido pelo `multer`.
