# DSAPlayground

- This project(playground) makes data structures and algorithms accessible via a Command Line Interface. 
- You can store various data structures in the cloud and come back to them when needed to perform more operations on them with all progress saved.

## Installation

Use the package manager [npm](https://www.npmjs.com/) to install [DSAPlayground](https://www.npmjs.com/package/dsacli) globally.

```bash
npm i -g dsacli
```

## Usage

## Tech Stack

### Client
- The client is a command line interface built with Node which is accessible via a NPM package. 

- It uses prompts as the base to handle and parse inputs and axios to make HTTP requests to the server.

### Server
- The server utilizes Node and uses Express to handle routes.

- Authentication and storing all the various data structures and algorithms are done using Firebase and Firestore.

- The server is Dockerized and deployed using Qovery.
