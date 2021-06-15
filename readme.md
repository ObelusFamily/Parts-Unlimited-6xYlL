# Welcome to the Parts Unlimited repo

## Dependencies 

### Main
- "concurrently": "^6.0.0",
- "pg": "^8.5.1",
- "pg-hstore": "^2.3.3",
- "sequelize": "^6.6.2"
### Frontend
- "bootstrap": "^4.6.0",
- "history": "^4.6.3",
- "marked": "^0.3.6",
- "node-sass": "^5.0.0",
- "prop-types": "^15.5.10",
- "react": "^16.3.0",
- "react-dom": "^16.3.0",
- "react-redux": "^5.0.7",
- "react-router": "^4.1.2",
- "react-router-dom": "^4.1.2",
- "react-router-redux": "^5.0.0-alpha.6",
- "redux": "^3.6.0",
- "redux-devtools-extension": "^2.13.2",
- "redux-logger": "^3.0.1",
- "superagent": "^3.8.2",
- "superagent-promise": "^1.1.0"

## Installation

First, you must install yarn by running the command `npm install --global yarn`. You can check it is correctly installed with `yarn --version`.
Then to install dependencies you must run `yarn` or `yarn install` on both the main directory and the frontend directories.
For the backend directory, make sure you have rails installed by running `sudo gem install rails`, and install dependencies with `bundle install`.

## Running the app

To start the app use: `yarn start` on the main directory, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@janesmithwilco` as reviewer.
