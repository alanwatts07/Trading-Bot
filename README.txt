# Jupiter Trading Bot

This repository contains the source code for the Jupiter Trading Bot. The bot is written in TypeScript and consists of two main files: `bot.ts` and `index.ts`.

## Installation

To install the necessary dependencies, run the following command:
ts-node index.ts

Make sure index.ts (the client side file) is updated according to your own threshold prices and percentages. 

The bot uses quicknode end points and a metis end point which can be: https://public.jupiterapi.com

The bot will execute one trade with USDC when the sol price drops below your threshold... it will then scan market until price is up by a default of 1.5% and then execute another swap..

Just shows how to use the jupiter api for a simple trade bot. 