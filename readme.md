# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To start setting up work environment follow the next steps:
1. [Download Docker](https://docs.docker.com/get-docker/)
2. follow the install flow.
3. after installing docker, make sure your Docker is installed correctly by running 
`docker -v` and  `docker-compose -v` in the terminal. you should get back the versions you installed.
4. then run `docker-compose up` in the terminal **from the location of your root directory**.
5. make sure everything is working by going to <http://localhost:3000/api/ping>
