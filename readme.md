# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Navigate to the provided link and click on Code, copy the HTTPS url 
Within terminal, git clone <HTTPS url> into the directory you want
Install Docker per instructions provided
To confirm docker is installed and working `docker -v` and `docker-compose -v`
Once confirmed, navigate to the project root directory and run `docker-compose up`
Once installation is complete click on provided link to make sure backend is connected