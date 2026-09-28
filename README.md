# 🛒 Cadastro de Produtos - Desafio PHP & MySQL

Projeto desenvolvido para o cumprimento do **Desafio 2 (`10a_desafio2.md`)**, com foco em manipulação de banco de dados, criação de formulários e validação de dados no backend usando PHP e MySQL.

---

## 📌 Funcionalidades

- **Criação do Banco de Dados**: Script de inicialização da base `exercicio` e tabela `produtos`.
- **Formulário de Cadastro**: Interface limpa para envio de *Nome do Produto* e *Preço*.
- **Validação Server-Side (PHP)**:
  - Valida se o nome do produto foi preenchido.
  - Valida se o preço informado é numérico e maior que zero (`> 0`).
- **Segurança**: Utilização de *Prepared Statements* com **PDO** para proteção contra **SQL Injection**.
- **Feedback Interativo**: Mensagens estilizadas de sucesso e erro na própria página.

---

## 🛠️ Tecnologias Utilizadas

* **PHP 8.x**
* **MySQL / MariaDB**
* **HTML5 & CSS3**

---

## 📂 Estrutura do Repositório

```text
.
├── 10a_desafio2.php   # Código-fonte principal (Formulário + Lógica PHP + PDO)
├── schema.sql         # Script SQL de criação do banco e tabela
└── README.md          # Documentação do projeto
