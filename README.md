# Flask Boilerplate #

This is a boilerplate for flask application made for quick start of flask projects.

## Instructions ##

- Install and run dependencies on virtualenv:

  ```bash
  pipenv install
  pipenv run
  ```

- Migrate the database:

  ```bash
  make create_db
  make db_init
  make db_migrate
  ```

- Upgrade the database:

  ```bash
  make db_upgrade
  ```

- Now run:

  ```bash
  make run
  ```

  Your server will run at <http://127.0.0.1:5000/>

- Run tests:

  ```bash
  make test
  ```
