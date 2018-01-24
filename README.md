# Elixir Pheonix sample project

Sample project based on a few different posts that containerize a pheonix web app with docker and docker-compose.

## Getting Started

Install elixir and pheonix by following the official sites.

Create a new pheonix project using the mix command.

Use the example Dockerfile and docker-compose.yml files from this repo.

`docker-compose up --build` and the app should log errors unable to connect to the database.

Connect to the running web container and run the `mix ecto.create` to create the database and resolve the errors.


