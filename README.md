# djangoconus22-tutorial

This Repo contains the reference for the tutorial at [DjangoCon US 22](https://2022.djangocon.us/tutorials/using-django-for-serving-rest-apis-with/).

Instructions to run this project.

# Environment Initiatization

- [Install Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer)
- [Install Docker](https://docs.docker.com/engine/install/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)
- Unable to install `psycopg2`, Firstly make sure to install the `postgres` server than only the `psycopg2` package will run, so make sure to install the `postgres` server in yout machine, but we don't need to run the `psycopg2` server. If it does't solve your issues than please check the below links.
  - [Windows](https://stackoverflow.com/questions/33215558/unable-to-install-psycopg2-on-windows)
  - [Linux](https://stackoverflow.com/questions/47318227/cannot-install-psycopg2-ubuntu)
  - [Mac](https://stackoverflow.com/questions/33866695/error-installing-psycopg2-on-macos-10-9-5)

# Running your project locally

## Spin up the Database

- `poetry shell`
- `poetry install`
- `python manage.py runserver`
