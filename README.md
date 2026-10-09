# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full Stack Open course

## Deployed application

https://fs-pokedex-hidden-willow-4064.fly.dev/

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server

`npm test` to run tests

`npm run eslint` to run eslint

`npm run build` to make a production build

`npm run start-prod` to run your production build


## Continuous Integration

GitHub Actions runs the lint, build, unit tests, and end-to-end tests when a pull request targets the `main` branch.

Deployment to Fly.io runs only for pushes to the `main` branch.