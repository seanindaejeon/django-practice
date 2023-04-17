# django-practice

```bash
docker build .
docker-compose build

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose up
http://localhost:8000/

git add .
git commit -am "Added GitHub Actions."
git push origin

git credential-osxkeychain erase
host=github.com
protocol=https

git config --global credentials.helper osxkeychain

git push origin

git config --local credential.helper ""
git config --global credential.helper ""

```