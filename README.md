[![CircleCI](https://circleci.com/gh/kingokeke/bond-exercise-react.svg?style=svg&circle-token=9e0ca6f4d21d123ef71fc0ce64a99784e07d7e0f)](https://circleci.com/gh/kingokeke/bond-exercise-react)

# Exercise React

Run the server with

```bash
yarn
yarn start
```

Or if you use npm

```bash
npm install
npm start
```

---

Then run the client

```bash
cd client
yarn
yarn start
```

Or if you use npm

```bash
cd client
npm install
npm start
```

---

The server part of this system is already designed and exposes a set of REST endpoints via the `/api` route and a GraphQL endpoint.

The client has been setup to consume graphql if you chose to use that instead.

## Task

Build 3 views

- A dashboard with stats and the trips listed in a table.
- A drivers' master-detail page
- A trip page to show the detail for a single trip
