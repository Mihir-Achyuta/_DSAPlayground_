# DSAPlayground

- This project(playground) makes data structures and algorithms accessible via a Command Line Interface. 

- You can store various data structures in the cloud and come back to them when needed to perform more operations on them with all progress saved.

- Just install it using npm, create an account, and get started. 

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install [DSAPlayground](https://www.npmjs.com/package/dsacli) globally.

```bash
npm i -g dsacli
```

## Usage

## Tech Stack

### Client
- The client is a Command Line Interface built with Node which is hosted on NPM and accessible via a NPM package. 

- It uses Prompts as the base to handle and parse user inputs and Axios to make HTTP requests to the Node server.

- Users can currently store, modify, and view Stacks, Queues, Linked Lists, Heaps, and Tries client side.

### Server
- The server is built with Node and uses the Express framework to handle routes to create the API.

- Authentication is done using Firebase and storing all the various data structures and algorithms are done with Firestore.

- The server is Dockerized and is deployed on a Qovery instance.
