# Mario Blackjack

A Blackjack card game, made using React.js and Firebase for storing data.

## Table of Contents 📋

- [Getting Started](#getting-started-)
  - [Prerequisites](#prerequisites)
- [Running the Project](#running-the-project-%EF%B8%8F)
  - [Installation](#installation)
  - [Testing](#testing)
- [Project Structure](#project-structure-)
- [Demo](#demo-)
- [References](#references-)

## Getting Started 🚀

### Prerequisites

Before you get started, ensure you have the following installed:

- [Node.js and NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm);

## Running the Project 🏃‍♂️

### Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/joaolessab/mario-blackjack--react.js-firebase.git
cd app
yarn
```

### Local execution

1. You will need to set credentials for you Firebase database (check References section - for more details);
- 1.1. To create your own `.env` file, run: `cp .env.example .env`;
- 1.2. Change the variable values of the `.env` file generated, using now your own Firebase credentials;
2. Run `yarn start`;
3. Open you browser at `https://localhost:3000/` (usually it's the 3000 port, but it can change. Check your terminal);

### Testing

1. Run `yarn test`;
2. Press `a` to run all the tests;

## Project Structure 📁

    .
    ├── ...
    ├── docs                                # Documentation files
    ├── app                                 # App main folder
    │   |── components/                     # Components broken into small pieces
    │   |── pages/                          # Main components views that consumes the components
    │   |── assets/                         # Images, fonts and icons for the app
    │   |── utils/                          # Utils that concentrates the game logic and some string manipulations
    │   |── context                         # Context to store and control app data
    │   │      ├── AuthProvider.tsx         # Main responsible file for controlling the app login and credentials
    │   |── firebase                        # Folder that has all the files related to the Firebase connection
    │   │      ├── firebaseConfig.ts        # Firebase default file reading credentials and setting up the library
    │   ├── App.js                          # Main file of the project
    │   ├── package.json                    # Libraries and dependencies of the project
    │   └── ...                             # etc.
    └── ...

## Demo 🎥

## References 📚

- [Firebase: Setting up a project](https://reactnative.dev/](https://firebase.google.com/docs/web/setup)https://firebase.google.com/docs/web/setup);
