# WADT Learns GraphQL + VueJS
This project is a starter project that will run a VueJS Web App that is connected to GraphQL server via Apollo.

This project was adapted from Andy Li's 3 part blog series on GraphQL: https://www.vuemastery.com/blog/why-you-should-use-vue-graphql/

This starter project is used by WD4307 Web Application and Development Tools module for Assignment 4. Assignment 4 requires further modification of the code to include TailwindCSS and modification of the mock data found in GraphQL server.

# Project Details
This project have 2 parts:

1) my-app - the VueJS Web App frontend
2) my-api - GraphQL server that my-app connects to

# How to use/install this project
You may fork this repo by pressing the fork button on the top-right of GitHub page. Then use that repo version as your starting point, then follow the instructions below.

1) git clone this repo: `git clone https://github.com/PoliteknikBrunei-WADT/wadtlearnsgraphqlvuejs`
2) `cd wadtlearnsgraphqlvuejs`
3) First pull dependencies for each folder, i.e. `cd my-app && npm install` do the same for my-api folder and run `npm install`
4) To run the frontend server, while inside my-app folder run: `npm run dev` run this this in the background
5) The frontend server needs data from GraphQL server, thus go inside my-api folder (using a new terminal window) and run: `node server.js` (alternatively you may use nodemon - `npm install -g nodemon` then run `nodemon server.js`)

# License
©️ Bahit Hamid 2021
