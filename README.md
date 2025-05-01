🎬 Catálogo de Filmes

O Catálogo de Filmes é um projeto web desenvolvido com Django, feito pra cadastrar, listar e visualizar filmes com aquela interface gostosinha e funcional. Ideal pra organizar suas sessões de cinema e ainda dar um showzinho de backend com Python.

🚀 Começando

Siga os passos abaixo pra rodar o projeto localmente:

1. Clone o repositório

git clone https://github.com/Nick2901/Django-CatalogoDeFilmes.git
cd Django-CatalogoDeFilmes

2. Crie e ative um ambiente virtual

Windows:

python -m venv venv
venv\Scripts\activate

Linux/macOS:

python -m venv venv
source venv/bin/activate

3. Instale as dependências

pip install -r requirements.txt

4. Rode as migrações do banco de dados

python manage.py migrate

5. Inicie o servidor

python manage.py runserver

Depois disso, acesse o projeto pelo navegador em http://127.0.0.1:8000/

Faça o cadastro de filmes pelo http://127.0.0.1:8000/admin

🧰 Requisitos

Python 3.12 ou superior

Django 5.x

SQLite (ou outro banco de dados, se quiser configurar)
