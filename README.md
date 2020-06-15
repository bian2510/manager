# README

## build the image and run docker-compose:

`docker-compose build`
`docker-compose up`

## Create the database and run migrations.

### In other terminal run:

`docker-compose run web bundle exec rails db:create`
`docker-compose run web bundle exec rails db:migrate`