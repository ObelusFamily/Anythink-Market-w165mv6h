# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

 - Create your codespace
 - Run docker-compose up in your codespace terminal
 - Once docker-compose finishes loading up, the backend should be running and able to connect to the database. 
 - After the server is up, make sure you test it by pointing your browser to https://oybektoirov-silver-umbrella-4gr7j4757jcj66q-3000.preview.app.github.dev/api/ping
 - It’s time to check the frontend and make sure it’s connected to the backend.
 - If everything is working properly, you’ll be able to create a new user on https://oybektoirov-silver-umbrella-4gr7j4757jcj66q-3001.preview.app.github.dev/register
