# Docker Compose file for Laravel & Tailwind CSS testing

### How to use
* First clone this repo
* Create a new Laravel app with `laravel new code` (or check the [docs](https://laravel.com/docs/11.x) on how to create a new instance for your situation)
* Code `.env` into the `code` directory: `cp .env ./code/`
* Run `docker compose build` to build the Dockerfile
* Run `docker compose up -D` to start the environment
* Goto http://localhost:8000 to check the laravel build

You can check the logs with `docker compose logs -f` (use ctrl-c to exit)