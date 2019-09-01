# October

October is a visual and pseudonymous social network designed for the attention economy based around coins.

## Features

* News Feed: Discover content in your personalized feed. Like and dislike posts and comments.
* Composer: Create memes. Post links, images, and text.
* Anonymous: Tip, Like, Post, and Comment as yourself or anonymously.
* Tip Coins: Support content creators by tipping them with Coins. You can tip as yourself or anonymously.
* Leaderboard: Get bragging rights for earning the most Coins. Each like and comment on your content earns you 1 Coin.

## Technology

* October is built in React, React Native and Go. Mobile- and web-based clients talk to the Go backend using WebSockets and GraphQL.
* React powers both mobile and web clients. The October web app is written in ReactJS, while React Native powers native mobile applications.
* All clients share platform-independent state management using Redux.
* All communication between clients and the backend pass through our API Engine written in Go.
* Data is stored in a PostgreSQL database.
* Core services are supported with a number of local and third party dependencies.

## Setup

Want to set it up and give it a try? Run

```
git clone git@github.com:october93/october.git
git clone git@github.com:october93/engine.git
git clone git@github.com/october93/web.git
cd october
docker-compose up
```
