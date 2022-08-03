# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Node.js

<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/dev-setup-resources/master/res/nodejs.png">
  <br/>
</p>

#### Installation

open terminal and isntall these package

    $ sudo apt update
    $ sudo apt install node docker-ce docker-compose
    $ npm install --global yarn


#### Npm usage

To start project a got to frontend and backend directories and update node package using your project's `package.json` file:

    $ yarn install

T
To find outdated packages (locally or globally):

    $ npm outdated [-g]

To upgrade all or a particular package:

    $ npm update [<package>]

To uninstall a package:

    $ npm uninstall <package>

### Run the project

The After setting up package compose and start docker container:

    $ docker-compose up

open the links to check the project:

     http://localhost:3000/api/ping http://localhost:3001/register


