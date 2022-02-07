# Book Search Engine

Built a social media app that allow users to be able to sign up and create an account, post their thoughts, and interact with other users.

## Table of Contents

* [Setup](#setup)
* [Usage](#usage)
* [Deployment](#deployment)
* [Contributing](#contributing)
* [License](#license)

## Setup
:floppy_disk:

Uses the following tools in this repository:

- [React](https://reactjs.org/)
  - Open-source, declarative, component-based JavaScript library for building user interfaces. It’s maintained by Facebook, and it can be used to develop of single-page applications (SPA).
- [GraphQL](https://graphql.org/)
  - GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
- [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
  - Open-source, spec-compliant GraphQL server that's compatible with any GraphQL client, including Apollo Client. Uses apollo-server-express package to integrate GraphQL into Express.js server, and the @apollo/client package to make requests from React front end to the GraphQL API.
- [Apollo Client](https://www.apollographql.com/docs/react/)
  - All-in-one dependency that enables connection to a GraphQL API server and execute queries or mutations using their own special form of React Hooks.
- [React Router](https://graphql.org/)
  - Collection of navigational components that compose declaratively with the application, allowing single-page React applications behave more like multi-page applications.
- [concurrently](https://graphql.org/)
  - Runs multiple processes, or servers, from a single command-line interface, rather than opening multiple terminals to start multiple servers. Tracks multiple outputs in one place and will stop all processes if one fails.
- [jsonwebtoken](https://graphql.org/)
  - JSON Web Tokens, or JWTs, are an alternative to using session cookies for authentication.
- [jwt-decode](https://graphql.org/)
  - Helps decode JWTs from their Base64Url encoding. Extracts non-sensitive data such as token's expiration date to see if it's expired before making a request to the server.
- [faker](https://graphql.org/)
  - Generates massive amounts of fake data in the development environment of your Node.js applications.
- [nodemon](https://graphql.org/)
  - Simplifies development environment by automatically restarting Node.js applications when file changes in the directory are detected.

Repository splits into `client` and `server` sections to handle different parts of the development mode.

## Usage
:keyboard:

If the repository was cloned, run the files with `npm install` and start the server with `npm run develop`.

User is able to log in, sign up, post thoughts and add reactions to thoughts. user is able to navigate to other user's profiles and add them to their friends list.

## Deployment
:computer:

[Deployed Website Link](https://deep-thoughts-proj.herokuapp.com/)

## Contributing
:octocat:

[paperpatch](https://github.com/paperpatch)

## License
:receipt: