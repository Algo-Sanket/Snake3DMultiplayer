# Snake3D Multiplayer Game

This repository contains the code for the Snake3D multiplayer game using Docker and Colyseus.

## Video Demo

Click the image below to watch the video demo:

[![Watch the video](https://img.youtube.com/vi/<VIDEO_ID>/0.jpg)](https://github.com/Algo-Sanket/Snake3DMultiplayer/blob/main/Screen%20Recording%202024-07-17%20023104.mp4)

# The movement of snake will be through the cursor when click the right mouse button
# To play the game, users must download it and then execute Docker and npm commands. Deploying through Colyseus on AWS or Azure requires a subscription for public deployment of the container. Alternatively, Unity Photon Fusion offers a potentially more cost-effective solution for deploying the game online publicly.

Setup Instructions:
Docker:

Navigate to the server folder:

bash

cd server
Start the container:

bash

docker-compose up
NPM:

Navigate to the server folder with source code:

bash

cd server/SnakeMultiplayerServer
Install dependencies:

bash

npm install
Start the server:

bash

npm start
