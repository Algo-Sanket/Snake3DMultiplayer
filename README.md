# Snake3D Multiplayer Game

This repository contains the code for the Snake3D multiplayer game using Docker and Colyseus.

## Video Demo

Click the image below to watch the video demo:

[![Watch the video](https://img.youtube.com/vi/<VIDEO_ID>/0.jpg)](https://github.com/Algo-Sanket/Snake3DMultiplayer/blob/main/Screen%20Recording%202024-07-17%20023104.mp4)

## Docker Setup

> **WARNING**
> Required [docker](https://docker-docs.uclv.cu/engine/install/) and [docker-compose](https://docker-docs.uclv.cu/compose/install/).

1. Go to the server folder:
    ```bash
    cd server
    ```

2. Start container:
    ```bash
    docker-compose up
    ```

That's all. Now you have a container running on your machine with a server for the game on port `2567`. If this port is busy, there will be problems, so you can change it in the corresponding [docker compose file](https://github.com/Algo-Sanket/Snake3DMultiplayer/blob/main/server/docker-compose.yml).

## NPM Setup

> **WARNING**
> Required [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).

1. Go to the server folder with the source code:
    ```bash
    cd server/SnakeMultiplayerServer
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

That's all. Now you can start the game client and connect to the game.
