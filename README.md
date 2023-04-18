# django-practice

```bash
docker build .
docker-compose build


docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose run --rm app sh -c "python manage.py test"
docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "python manage.py test && flake8"

docker-compose up
http://localhost:8000/
docker-compose down
docker-compose build

git add .
git commit -am "Added GitHub Actions."
git push origin

docker-compose run --rm app sh -c "python manage.py startapp core"

```
