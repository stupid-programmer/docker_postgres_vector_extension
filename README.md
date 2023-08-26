# docker_postgres_vector_extension
A simple docker config for postgres with pgvector extension. The extension documentation can be found at *[the pgvector repo](https://www.markdownguide.orghttps://github.com/pgvector/pgvector)* including instructions to verify the vector field is working.

#### To run go to the root of the directoy and run docker compose up

- cd postgres_pg_vector_container
- docker compose up


The connection details and database name can be set within the docker-compose.yml files, the defaults are set to the following.

  - POSTGRES_USER=postgres
  - POSTGRES_PASSWORD=postgres
  - POSTGRES_DB=vectorexample


  ##### Needless to say, this is not meant to be for production use.