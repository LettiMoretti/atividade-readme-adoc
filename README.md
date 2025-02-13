= 📝 Booky - Sistema de Gerenciamento de Biblioteca

:icons: font
:toc: left
:toclevels: 2

== 🎯 Sobre o Projeto
O **Booky**, um **sistema de gerenciamento de biblioteca**, foi desenvolvido para facilitar o processo de empréstimo, devolução e gerenciamento de livros em uma biblioteca. Através da aplicação, é possível gerenciar empréstimos de livros, disponibilidade de exemplares, cadastro de usuários e gerar relatórios de atividades. O sistema visa **melhorar a experiência do usuário** e **otimizar a administração da biblioteca**, garantindo uma gestão eficiente e eficaz.

== 🚀 Recursos
- Cadastro e gerenciamento de livros com informações detalhadas (título, autor, ISBN, etc).
- Criação e modificação de empréstimos de livros, com opções de data de empréstimo e devolução.
- Visualização da disponibilidade dos livros em tempo real.
- Geração de relatórios de empréstimos, devoluções e multas.
- Notificação de usuários sobre empréstimos e devoluções.
- Sistema de login e autenticação para administradores e usuários.

== 📦 Tecnologias Utilizadas
- Angular (Frontend): Framework utilizado para o desenvolvimento da
interface de usuário, permitindo uma aplicação interativa e responsiva.
- Spring Boot, Java (Backend): Framework utilizado para o desenvolvimento da API, que gerencia os empréstimos, os livros e os usuários.
- MySQL (Banco de Dados): Banco de dados relacional utilizado para armazenar informações sobre empréstimos, usuários e livros.
- JWT, JSON Web Tokens (Autenticação): Utilizado para garantir a segurança no processo de autenticação e autorização de usuários.

== 🎮 Como Executar
**1. Clone o Repositório**

Clone o repositório para o seu ambiente local com o comando:

----
git clone https://github.com/usuario/sistema-biblioteca.git
----

**2. Instale as Dependências do Frontend**

Navegue até o diretório do frontend e instale as dependências com npm:

----
cd sistema-biblioteca/frontend
npm install
----

**3. Instale as Dependências do Backend**

Navegue até o diretório do backend e instale as dependências com Maven:

----
cd sistema-biblioteca/backend
mvn install
----

**4. Configuração do Banco de Dados**
Crie um banco de dados MySQL e configure as credenciais no arquivo application.properties do backend. Em seguida, execute as migrações para criar as tabelas necessárias:

----
spring.datasource.url=jdbc:mysql://localhost:3306/biblioteca
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
----

**5. Inicie o Servidor Backend**

Inicie o servidor do backend com o comando:
----
mvn spring-boot:run
----

**6. Inicie o Servidor Frontend**
Inicie o servidor do frontend com o comando:
----
ng serve
----

**7. Acesse a Aplicação**:

Abra o navegador e acesse a aplicação na URL: http://localhost:4200.

== 📚 Documentação da API

