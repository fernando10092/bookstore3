## Orientações

1. Clone this project
   git clone github.com/maxh33/bookstore

2. Install dependencies:
   cd bookstore
   poetry install

3. Run local dev server:
   poetry run manage.py migrate
   poetry run python manage.py runserver

   
4. Run docker dev server environment:
   docker-compose up -d --build 
   docker-compose exec web python manage.py migrate

http://127.0.0.1:8000/bookstore/v1/product/