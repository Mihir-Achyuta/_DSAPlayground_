# DSAPlayground

- This project(playground) makes data structures and algorithms accessible via a Command Line Interface. 

- You can store various data structures in the cloud and come back to them when needed to perform more operations on them with all progress saved.

- Just install it using [NPM](https://www.npmjs.com/package/dsacli), create an account on the CLI, and get started. 

## Installation

Use the package manager [NPM](https://www.npmjs.com/) to install [DSAPlayground](https://www.npmjs.com/package/dsacli) globally.

```bash
npm i -g dsacli
```

## Usage

## Tech Stack

### Client
- The client is a Command Line Interface built with [Node](https://nodejs.org/en/) which is hosted on [NPM](https://www.npmjs.com/) and accessible via a NPM package. 

- It uses [Prompts](https://www.npmjs.com/package/prompts) as the base to handle and parse user inputs and [Axios](https://www.npmjs.com/package/axios) to make HTTP requests to the Node server.

- Users can currently store, modify, and view Stacks, Queues, Linked Lists, Heaps, and Tries client side.

### Server
- The server is built with [Node](https://nodejs.org/en/) and uses the [Express](https://expressjs.com/) framework to handle routes to create the API.

- Authentication is done using [Firebase](https://firebase.google.com/) and storing all the various data structures and algorithms are done with [Firestore](https://firebase.google.com/docs/firestore).

- The server is [Dockerized](https://www.docker.com/) and is deployed on a [Qovery](https://www.qovery.com/) instance.
