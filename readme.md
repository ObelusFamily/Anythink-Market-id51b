# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
Instructions for First Run: 

1. Install [Docker](https://docs.docker.com/get-docker/) on your computer, if not yet installed. 
2. Verify the Docker installation by executing `docker -v` or `docker-compose -v` into the terminal or command prompt. 
3. Navigate to the project's root directory. 
4. Load the front and back end by executing `docker-compose up`. 
5. To verify that backend is running: enter [http://localhost:3000/api/ping](http://localhost:3000/api/ping) into your web browser. The page should load successfully. 
6. To verify that frontend is running: enter [http://localhost:3001/register](http://localhost:3001/register) into your web browser. The page should load successfully. 