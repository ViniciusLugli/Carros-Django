# Carros PycodeBR

Este projeto é uma aplicação web desenvolvida com Django para cadastro, listagem e pesquisa de veículos. O objetivo principal é servir como material de estudo para quem deseja aprender Django, manipulação de formulários, autenticação de usuários e upload de imagens.

## Funcionalidades

- Cadastro de novos carros com foto, marca, modelo, ano de fabricação, ano do modelo, placa e valor.
- Listagem de carros em uma galeria visual.
- Pesquisa de carros por modelo, marca ou ano.
- Cadastro e login de usuários.
- Upload e exibição de fotos dos veículos.
- Interface moderna e responsiva.

## Tecnologias Utilizadas

- Python 3
- Django 5
- SQLite3
- HTML/CSS
- [Pillow](https://python-pillow.org/) para manipulação de imagens

## Como rodar o projeto

1. Clone o repositório.
2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
3. Realize as migrações:
   ```sh
   python manage.py migrate
   ```
4. Crie um usuário administrador (opcional):
   ```sh
   python manage.py createsuperuser
   ```
5. Inicie o servidor:
   ```sh
   python manage.py runserver
   ```
6. Acesse `http://localhost:8000/cars/` no navegador.

## Observações

- O projeto é voltado para fins de estudo e aprendizado.
- Não utilize em produção sem as devidas adaptações de segurança.
- O upload de imagens é salvo na pasta `media/cars/`.
