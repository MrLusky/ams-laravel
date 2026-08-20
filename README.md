# AMS Laravel

Projeto desenvolvido para demonstrar a criação de um banco de dados
MySQL utilizando Laravel Migrations.

## Estrutura do banco

### Users
Armazena os usuários do sistema.

### Profiles
Armazena o perfil de cada usuário.
Relacionamento: Users 1:1 Profiles.

### Posts
Armazena as publicações dos usuários.
Relacionamento: Users 1:N Posts.

### Tags
Armazena as categorias/tags dos posts.

### Post_Tag
Tabela pivô responsável pelo relacionamento N:M entre Posts e Tags.

## Relacionamentos

Users 1:1 Profiles
Users 1:N Posts
Posts N:M Tags

## Tecnologias

- Laravel
- PHP
- MySQL
- Laravel Migrations