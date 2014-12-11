We store much of our data in postgres. The ORM that we use on our api server is [knex](http://knexjs.org/) and [bookshelf](http://bookshelfjs.org/)

## Debugging (repl)
  * On your host computer first find the postgres container `docker ps | grep postgres`
  * Run bash in a running container with `docker exec -it <CONTAINER ID> bash`
  * Looking at the database:
    * `su postgres`
    * `psql bunsen_dev`