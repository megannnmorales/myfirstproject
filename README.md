# myfirstproject
# Employee Records (MERN)

A full-stack employee management app, built by following MongoDB's
[MERN stack tutorial](https://www.mongodb.com/resources/languages/mern-stack-tutorial).

I followed the tutorial step by step to get hands-on practice with a full JavaScript stack. The structure and code come from the tutorial; the design is not my own.

## What it does
- Lists employee records (name, position, level)
- Creates, edits and deletes records

## What I practised
- Building a REST API with Express and Node.js
- Connecting to a MongoDB Atlas database
- Building a React frontend with Vite, React Router and Tailwind CSS
- Connecting the client to the API with `fetch`

## Running it
1. Clone the repo
2. In `server/`, create a `config.env` with your own `ATLAS_URI` and `PORT=5050`
3. In `server/`: `npm install`, then `node --env-file=config.env server`
4. In `client/`: `npm install`, then `npm run dev`
5. Open http://localhost:5173

## Stack
MongoDB Atlas, Express, React, Node.js, Vite, Tailwind CSS