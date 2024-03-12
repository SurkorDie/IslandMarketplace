# Island marketplace full stack project

## Description

## Dependencies

**Project Dependencies**

- "axios": "^0.21.1",
- "concurrently": "^6.0.0",
- "dotenv": "^8.2.0",
- "express": "^4.17.1",
- "helmet": "^4.4.1",
- "if-env": "^1.0.4",
- "mongoose": "^5.12.2"

**Development Dependencies**

- "@babel/eslint-parser": "^7.13.10",
- "@babel/plugin-syntax-jsx": "^7.12.13",
- "@babel/preset-react": "^7.12.13",
- "@babel/runtime": "^7.13.10",
- "eslint": "^7.22.0",
- "eslint-config-prettier": "^8.1.0",
- "eslint-plugin-import": "^2.22.1",
- "eslint-plugin-jest": "^24.3.2",
- "eslint-plugin-jsx-a11y": "^6.4.1",
- "eslint-plugin-prettier": "^3.3.1",
- "eslint-plugin-react": "^7.23.1",
- "eslint-plugin-react-hooks": "^4.2.0",
- "jest": "^26.6.3",
- "nodemon": "^2.0.7",
- "prettier": "^2.2.1",
- "ts-node": "^9.1.1",
- "typescript": "^4.2.3"

## Installation Requirements

You will need [NodeJS][nodejs] installed for use with this project.

You will also need the latest version of [MongoDB][mongodb] installed locally on your machine.

## Configuration

To configure this application for use, you should create a `.env` file with your database information. For convience, a sample enviroment variable file can be found in the root directory with the name of: `.env.example`.

> After installing the dependencies and initializing the project (instructions below) you will need to go into the `package.json` file in your `client/` folder and add `"proxy": "http://localhost:3001"` to this file.

## Usage

**Getting Started**

To get started with this project, you'll want to install the required dependencies and the React frontend with this command:

```shell
npm run install:all
```
