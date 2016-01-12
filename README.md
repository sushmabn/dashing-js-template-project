#dashing-js-template-project


The [dashing-js npm package](https://github.com/fabiocaseri/dashing-js) has old dependencies and `npm install` fails.  A [fork of dashing-js](https://github.com/dodderjs/dashing-js) by [dodderjs](https://github.com/dodderjs) incudes updates for the dependencies, but it has not been merged into the main project. 

This repo includes that fork as a submodule, so you can get it all running without npm.

###How to Use

- Clone this repository

`git clone https://github.com/chriswhong/dashing-js-template-project.git`

- Install Submodules

`git submodule update --init --recursive`

- Install Dependencies for the dashing-js submodule

`cd dashing-js-template-project/submodules/dashing-js && npm install`

- Navigate back to the main directory and start the server 

`cd ../.. && node server.js`

You should be able to load the dashboard at `http://localhost:3030`

