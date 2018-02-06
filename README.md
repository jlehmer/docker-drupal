# Setup Drupal Container

* From the root directory of the project run `$ docker-compose up`
* Access locahost:8080 and walk through the DB setup process entering the following information:
  *  Database type: PostgreSQL
  *  Database name: postgres
  *  Database username: postgres
  *  Database password: example
  *  ADVANCED OPTIONS --> Database host: postgres

Keep in mind that the database setup will persist across container restarts, however, this DB setup step will need to be repeated if the container needs to be created again.
