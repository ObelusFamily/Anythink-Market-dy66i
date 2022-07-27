# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone the repo on github to your local machine

Download and install Docker for Linux, Windows or Mac

Check that docker and docker-compose are installed with the commands 'docker -v' and 'docker-compose -v'

run docker from within the repo directory directory (where the .yml file resides) by using the 'docker-compose up' command

If all went well, the docker containers should be running and they should be accessible. Verify with http://localhost:3000/api/ping

Navigate to http://localhost:3001/register and create a user