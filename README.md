Sistema LFA

Sistema de gerenciamento desenvolvido para o LFA — Lar Beneficente de Idosos, com o objetivo de centralizar e facilitar o gerenciamento das informações da instituição.

 Sobre o projeto

Atualmente, parte das informações do LFA é coletada e gerenciada através de diferentes formulários e planilhas, o que pode dificultar a organização, consulta e acompanhamento dos dados.

O objetivo deste projeto é desenvolver um sistema web que centralize essas informações em uma única plataforma, permitindo um gerenciamento mais organizado e eficiente.

Inicialmente, o sistema terá como foco o cadastro e gerenciamento das principais entidades envolvidas na instituição, além do acompanhamento de atividades e informações dos beneficiários.

 Objetivos
Centralizar os dados do LFA em um único sistema.
Facilitar o cadastro e gerenciamento de beneficiários.
Facilitar o cadastro e gerenciamento de voluntários.
Gerenciar empresas parceiras e apoiadoras.
Permitir o cadastro e acompanhamento de atividades.
Facilitar a consulta e atualização das informações.
Reduzir a dependência de planilhas e múltiplos formulários.
Implementar autenticação e controle de acesso.
Disponibilizar informações de forma organizada através de uma interface web.
Permitir a exportação dos dados para arquivos Excel.

 Principais entidades
Beneficiários

Representam os idosos atendidos pelo LFA.

O sistema deverá permitir:

Cadastro;
Consulta;
Edição;
Inativação;
Visualização das informações;
Acompanhamento de atividades.
Voluntários

Representam as pessoas que colaboram com o LFA.

O sistema deverá permitir o gerenciamento das informações dos voluntários e, futuramente, seu relacionamento com atividades.

Empresas

Representam empresas e organizações que apoiam ou colaboram com o LFA.

O sistema deverá permitir o cadastro e gerenciamento dessas informações.

Atividades

Representam atividades realizadas ou planejadas para os beneficiários.

O sistema deverá permitir o cadastro, acompanhamento e relacionamento das atividades com os beneficiários e voluntários.

 Autenticação e segurança

O sistema contará com autenticação de usuários para restringir o acesso às informações.

A princípio, está prevista a utilização de:

Spring Security;
Autenticação baseada em usuário e senha;
Senhas armazenadas de forma segura;
Controle de permissões por perfil de usuário;
Proteção dos endpoints da API.

Os níveis de acesso ainda serão definidos durante o levantamento de requisitos.

 Dashboard e acompanhamento

O sistema deverá possuir uma área central para acompanhamento das informações cadastradas.

Entre as funcionalidades planejadas estão:

Visualização dos beneficiários;
Visualização dos voluntários;
Visualização das empresas;
Acompanhamento das atividades;
Pesquisa e filtros;
Indicadores e informações gerais do sistema.

 Exportação de dados

Para manter a possibilidade de utilização dos dados em outros contextos, o sistema deverá permitir a exportação de informações para arquivos Excel (.xlsx).

A exportação poderá ser utilizada, por exemplo, para:

Relatórios;
Análises;
Backup operacional;
Compartilhamento de informações;
Processos administrativos

 Arquitetura

O projeto será desenvolvido utilizando uma arquitetura baseada em API REST.


Tecnologias planejadas:

React;
Tailwind CSS.
🛠️ Tecnologias
Backend
Java
Spring Boot
Spring Web
Spring Data JPA
Spring Security
PostgreSQL
Lombok
Maven
Frontend
React
Tailwind CSS
Outras tecnologias
Git
GitHub
Excel / .xlsx

 Status do projeto

Em desenvolvimento — fase de levantamento e análise de requisitos.

O projeto ainda está sendo estruturado. As entidades, regras de negócio, permissões e funcionalidades serão definidas durante o levantamento de requisitos junto ao LFA.
