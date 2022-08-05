# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Checking for completion

Once the docker-compose up process has loaded all necessary dependencies and checked for updates, and the webpack has completed, uvicorn should be running on port 3000.  

This can be confirmed by pointing your browser to http://localhost:3000/api/ping . This should confirm that the backend is working.

Once that has been confirmed as running without errors, the frontend connection should be verified.

Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

Once this is successful, the setup process is complete.

