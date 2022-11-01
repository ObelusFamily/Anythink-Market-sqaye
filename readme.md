# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Clone [this repository](https://github.com/ObelusFamily/Anythink-Market-sqaye)
  ```
  git clone https://github.com/ObelusFamily/Anythink-Market-sqaye.git
  ```
- To get started, Make sure you have [Docker](https://docs.docker.com/get-docker/) installed:
  ```
  https://docs.docker.com/get-docker/
  ```
  To check if setup was successful, run:
  ```
  docker-v
  ```
  And,

  ```
  docker-compose-v
  ```
  To load Anythink's Backend and frontend,from the root directory run: 

  ```
  docker-compose up
  ```
  Open the browser with `http://localhost:3000/api/ping`
