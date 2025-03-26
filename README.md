TF 25/03/2025

Este repositório é o projeto de um banco de dados para o TF de Implantação de Servidores. Ele foi feito para gerenciar as informações de uma escola.

Estrutura do Banco de Dados
O banco de dados tem três partes principais:

Aluno: Armazena dados dos alunos e informações sobre os responsáveis.

Turma: Armazena as turmas e seus horários.

Professor: Armazena os dados dos professores.

Relacionamentos
Aqui estão os relacionamentos entre as tabelas:

Aluno pertence a uma Turma (1:N)

Cada aluno está vinculado a uma turma.

Turma tem um Professor (1:N)

Cada turma tem um professor responsável por ela.

Como Usar
Certifique-se de ter o Docker instalado.

Vá até a pasta DB.

Execute o comando abaixo para levantar o banco de dados no Docker:
docker-compose up -d