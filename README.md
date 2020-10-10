# MyApp

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `cd assets && npm install`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix

# Setup Dockerfile and Manipulate Dockerfile

Manipulate Docker Container
   
  * Start docker-compose  `docker-compose up -d`
  * Stop docker-compse `docker-compose stop`
  * Login docker-compose `docker exec -it {container-id} bash` or `docker-compose ` or `docker-compose exec web /bin/bash`
  * Check docker-compose status `docker-compose ps`
  * Delete docker-compose `docker-compose down`

