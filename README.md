# 🛒 Projeto Amazon — E-commerce & Modelagem de Banco de Dados

Aplicação web de e-commerce inspirada na Amazon, desenvolvida com foco em modelagem relacional de banco de dados, arquitetura em camadas e boas práticas com **Python** e **Django**.

---

## 🎯 Objetivos do Projeto
* Modelagem e normalização de entidades de comércio eletrônico (Produtos, Categorias, Usuários, Pedidos e Carrinho).
* Implementação de regras de negócio para gerenciamento de estoque e checkout.
* Prática de consultas eficientes utilizando o Django ORM.

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Framework Web:** Django
* **Banco de Dados:** SQLite / PostgreSQL
* **ORM:** Django ORM

---

## 📁 Estrutura do Projeto
```text
Projeto-Amazon/
├── amazon/          # Configurações centrais do Django (settings, urls, wsgi)
├── backend/         # App principal com models, views, forms e lógica de negócio
├── manage.py        # Utilitário CLI do Django
└── requirements.txt # Dependências do projeto
```

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/samualmeid4/Projeto-Amazon.git
   cd Projeto-Amazon
   ```

2. **Crie e ative o ambiente virtual:**
   ```bash
   python -m venv venv
   # No Linux/macOS:
   source venv/bin/activate
   # No Windows (PowerShell):
   .\venv\Scripts\Activate.ps1
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute as migrações:**
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor de desenvolvimento:**
   ```bash
   python manage.py runserver
   ```
   Acesse a aplicação em `http://127.0.0.1:8000/`.

---

## 👨‍💻 Autor
Desenvolvido por [Samuel de Almeida Sousa](https://github.com/samualmeid4).
