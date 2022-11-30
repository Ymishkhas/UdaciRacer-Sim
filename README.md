# UdaciRacer-Sim

## Project Introduction
A simple game where you select a player and track, the game begins and you accelerate your racer by clicking an acceleration button. As you accelerate so do the other players and the leaderboard live-updates as players change position on the track. The final view is a results page displaying the players' rankings.

## Aim of the Project
This is the third project of the Intermediate JavaScript Nanodegree Program from Udacity. The main purpose of this project is to use the asynchronous skills gained in the course to complete the game.

This game makes use of Object Oriented programming techniques and Functional Programming as well as Asynchronous programming to run the game logic.

The game has three main views:

1. The form to create a race

2. The race progress view (this includes the live-updating leaderboard and acceleration button)

3. The race results view

## Getting Started

In order to run this game, we need to run two things: the game engine API and the front end.

### Start the Server

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-darwin-amd64`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-windows-amd64.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux-amd64` |


#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
- `cd` into the root of the project containing data.json 
- Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

### Start the Frontend

First, run `npm install && npm start` at the root of this project. Then you should be able to access http://localhost:3000.
