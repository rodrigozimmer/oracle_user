# Comando para criar usuário e alterar senha

## Criar usuário
CREATE USER nome_usuario IDENTIFIED BY senha;

## Pemissões 
GRANT CONNECT TO nome_usuario;

GRANT CONNECT, RESOURCE, DBA TO nome_usuario;

GRANT UNLIMITED TABLESPACE TO nome_usuario;

## Altera senha
ALTER USER nome_usuario IDENTIFIED BY nova_senha;
