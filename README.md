# Projeto Django para Exercício Prático 2 de Git

Este projeto é um sistema básico em Django que inclui funcionalidades CRUD para as entidades **Cliente**, **Produto** e **Venda**. Ele foi criado como um exercício prático para aprender e praticar o uso de Git.

## Requisitos

- Python 3.13
- pip (gerenciador de pacotes do Python)
- Virtualenv (opcional, mas recomendado para isolamento do ambiente)

## Configuração do Ambiente

### 1. Clone o Repositório

Primeiro, clone o repositório para a sua máquina local:

git clone https://github.com/saviotom/shopProject.git
cd shopProject

### 2. Crie e Ative um Ambiente Virtual

python -m venv venv

venv\Scripts\activate

### 3. Instale as Dependências do Projeto

pip install django

### 4. Configure o Banco de Dados

python manage.py migrate

### 6. Inicie o Servidor

python manage.py runserver

Acesse o projeto no navegador em http://127.0.0.1:8000/

### Integrantes e suas responsabilidades

guilherme maciel: tech lead
gabriel guady: desenvolvedor da ORD-002
joao borges: desenvolvedor da ORD-003 parte de templates com css.
gabriel coelho: desenvolvedor da ORD-003 parte de url, view e form

projeto final concluido.





