## Sistema de eventos

Projeto desenvolvido para o desafio "Modelo de domínio e ORM" do curso Java Spring.

Consiste na modelagem de um modelo de domínio de um sistema de eventos com Participantes, Atividades, Categorias e Blocos.

Os seguintes relacionamentos foram modelados utilizando Spring JPA:
- Cada atividade possui apenas 1 categoria e cada categoria pode estar relacionada a N atividades (1 - N);
- Cada atividade possui de 1 a N blocos, e cada bloco pode estar relacionado à apenas 1 atividade (1 - N);
- Cada participante pode participar de N atividades, e cada atividade pode conter N participantes (N - N).

O projeto foi implementado utilizando o banco in-memory H2  e o arquivo import.sql contém um seeding básico de dados.

## Requisitos para rodar o projeto

- Java JDK 21;
- Spring Web;
- Spring JPA;
- H2
