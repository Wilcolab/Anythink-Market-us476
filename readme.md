# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Step 1 : Clone this [repository](https://github.com/ObelusFamily/Anythink-Market-us476)

Step 2 : Install [Docker](https://docs.docker.com/get-docker/) by following the steps mentioned on the [site](https://docs.docker.com/get-docker/) .

 It might take some time but then it will be smooth sailing ⛵

Step 3 : You can verify docker is ready by running the following commands in your terminal:

```
docker -v
```

```
docker-compose -v
```
Then, run 
```
docker-compose up
``` 
from the project root directory to load Anythink's backend and frontend.

Step 4 : Sit back and relax, this will take some time.
If Docker is working correctly, the backend should be running and able to connect to your local database.

Step 5 : Let's test this by pointing your browser to http://localhost:3000/api/ping

You’re almost done! All you need to do now is run the frontend and make sure it’s connected to the backend.

Step 6 : Try to open the user registration page and create a test user. Here’s the link: http://localhost:3001/register.


Note: Now that you have everything set up, just make sure that you run all scripts on one of the containers you created using the 	`docker-compose up` 	command.  Also, you can use	 `docker exec`	 to run commands on a running container.
