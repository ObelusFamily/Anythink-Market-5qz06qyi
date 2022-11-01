# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Step 1

Create a codepace by clicking the button "Create codespace" and wait for it to boot.

### Step 2

You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.

### Step 3

After the server is up, make sure you test it by pointing your browser to https://clintmwi-verbose-space-dollop-wq7p7qx7gg52gwvr-3000.githubpreview.dev/api/ping

### Step 4

Now, it’s time to check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on https://clintmwi-verbose-space-dollop-wq7p7qx7gg52gwvr-3001.githubpreview.dev/register

### Note

Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up. Also, you can use docker exec to run commands on a running container.
