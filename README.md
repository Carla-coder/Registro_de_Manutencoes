## Projeto Registro de Manutenções

### Sistema de exemplo de API com testes utilizando o Insomnia

### Temas de aprendizado:

Banco de dados (MySQL)
API (NodeJS)
CRUD (NodeJS)
MVC (NodeJS)
Testes (Insomnia)

### Tecnologias	Utilizadas:

XAMPP - MySQL MariaDB	Banco de Dados Relacional
NodeJS - Framework para construção de APIs
VsCode - IDE
Insomnia - Ferramenta para testes unitários

### Como testar esta API

*. Necessário ter o ambiente/tecnologias acima instaladas

1. Clonar este repositório
2. Abrir com VsCode
3. Instalar o banco de dados
4. Abrir o XAMPP e clicar em start no MySQL, ou iniciar o MySQL da maneira que preferir.
5. Rodar os scripts de criação do Banco de dados e de população com dados de teste.
./bd/script.sql
./testes/testes.sql

6. Abrir um terminal cmd ou bash e navegar até a pasta ./api
cd api

7. Instalar as dependências do NodeJS
npm install

8. Executar com nodemon ou node server.js
nodemon
ou

npx nodemon
ou

node server.js

9. Abrir o aplicativo Insomnia e importar a coleção de rotas de testes que está na pasta ./testes/insomnia.json
10. Executar todos os testes
