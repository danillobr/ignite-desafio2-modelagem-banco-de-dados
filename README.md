<p align="center">
  <img src=".github/capa-ignite-nodejs.png" alt="Ignite Node.js">
</p>

<br>

<h1 align="center">
  Desafio 2: Modelagem do banco de dados
</h1>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## :computer: Descrição:
A aplicação deve ter uma tabela de gêneros (genres) para que cada jogo possa ter um ou mais gênero e, além disso, uma tabela orders deve existir para que um usuário consiga comprar um ou mais jogos na mesma compra.

## :hammer_and_wrench: Modelo conceitual:
<p align="center">
  <img src=".github/modelo-conceitual.png" alt="Ignite Node.js">
</p>

## :hammer_and_wrench: Esquema relacional:
- **users**(id_PK, email, first_name, last_name, created_at, update_at)
- **games**(id_PK, title, created_at, update_at)
- **genres**(id_PK, name)
- **orders**(user_id_FK, game_id_FK, amount, created_at)
- **receive**(genre_id_FK, game_id_FK) 
- 
## :hammer_and_wrench: Modelo relacional:
<p align="center">
  <img src=".github/modelo-relacional.png" alt="Ignite Node.js">
</p>
