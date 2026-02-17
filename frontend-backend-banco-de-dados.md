## **Como funciona Frontend, Backend e Banco de Dados?**

O desenvolvimento de um sistema web é dividido, geralmente, em três camadas principais:

* Frontend (client-side)
* Backend (server-side)
* Banco de Dados (database)

Essas três partes trabalham juntas para entregar uma aplicação funcional, segura e dinâmica.
##

### *2. Frontend (Interface do Usuário)*
O Frontend é a parte visual da aplicação, tudo aquilo que o usuário vê e interage.

*Ex:*
* Botões
* Formulários
* Telas de login
* Dashboards
* Animações
* Layouts


 
 *Linguagens usadas:*

* HTML → Estrutura
* CSS → Estilo
* JavaScript → Interatividade
* Frameworks: React, Vue, Angular

##

### *2. Backend (Lógica do Sistema)*

O Backend é o cérebro da aplicação. Ele processa regras de negócio e controla o fluxo de dados.

*Ex:*

* Autenticação de usuários
* Processamento de pagamentos
* Validação de dados
* Integrações com APIs externas

*Linguagens usadas:*

Node.js
* Python (Django, Flask)
* Java (Spring)
* PHP
* C#

##
### *3. Banco de Dados (Armazenamento)*

O Banco de Dados é onde as informações ficam armazenadas de forma estruturada e organizada.

*Ex:*

* Usuários cadastrados
* Produtos
* Pedidos
* Logs do sistema

*Linguagens usadas:*

* Relacionais (SQL)
* MySQL
* PostgreSQL
* SQL Server
* Não relacionais (NoSQL)
* MongoDB
* Firebase


##

## **Como elas se interagem?**

1. O usuário clica em um botão no Frontend
2. O frontend envia uma requisição HTTP para o Backend
3. O backend processa a lógica
4. O backend consulta o Banco de Dados
5. O banco retorna os dados
6. O backend envia a resposta ao frontend
7. O frontend exibe os dados na tela


### *Diferença entre elas:*


| Camada           | Função Principal        | Onde Roda        | Exemplo                |
|------------------|-------------------------|------------------|------------------------|
| Frontend         | Interface visual        | Navegador        | Tela de login          |
| Backend          | Regras de negócio       | Servidor         | Validação de senha     |
| Banco de Dados   | Armazenamento de dados  | Servidor / Cloud | Tabela de usuários     |
