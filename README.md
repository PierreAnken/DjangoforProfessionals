# Django for Professionals
Based on the book Django for Professionals from William S. Vincent

## Project commands

- `docker-compose up -d --build` --build = force rebuild, d = standalone run
- `docker-compose exec web python manage.py <some_command>` to run command in our docker
- `docker-compose exec web python -c "import secrets; print(secrets.token_urlsafe(38))"` generate a 51 digits key
- `docker-compose -f docker-compose-prod.yml up -d` sart with alternalte docker config
- `docker-compose exec web python manage.py check --deploy` get security recommendations