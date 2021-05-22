# Intelligent Driver Model
### By Usman Siddiqui

## What is it?
An implementation of the Intelligent Driver Model differential equations (Runge-Kutta Order 4) for simulating traffic flow.

## Setup

First ensure you have the latest version of [NodeJS](https://nodejs.org/en/) installed. Then:

- Navigate to `src/helpers/write_db.js` and configure the template database file as required (e.g. by changing vehicle parameters and adding latent behaviours). Use a NodeJS terminal to execute this script using `node write_db`. This will produce a corresponding JSON database file in `src/helpers/db`.

- Once the database is created, navigate to the root directory.

- If you wish to visualise the simulation in a browser, compile the `src/app.js` file using a module bundler such as WebPack.

- If you wish to store the data in a file, execute `node src/app.js` in a NodeJS terminal.

## Issues? Let me know

Get in touch with me at usman.siddiqui2209@gmail.com to report any bugs or issues.