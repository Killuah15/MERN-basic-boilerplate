# MERN-basic-boilerplate

This boilerplate is only made to have a very basic React app from the start. Most ReactJS boilerplates create code which is filled with features
some might not want. Since I just found boilerplates with some additional features, i wanted to create a really basic MERN Stack boilerplate
on which some could build greater apps upon.

## TODO
- integrate MongoDB
- apply Webpack middlewares for bundling and Hot Module Replacement in Express

## Quick Start

```sh
  clone this repository
  cd into your app directory
  npm install
  npm start
```

## Available Commands

1.  `npm start` - starts the development server with hot reloading enabled and express on port: $PORT or 3000

2.  `npm build` - bundles your ReactJS app (custom implementation/config might be needed)

## File Structure

# Webpack Configs

There is only one type of Webpack configs provided `webpack.config.js`. It uses babel-loader, css-loader and style-loader to bundle the ReactJS app into a functional ES5 webapp.

# Server

This MERN Boilerplate uses an Express backend to work. It can be found in `server/server.js`.

# V stands for View

View `Components` and `Containers` are placed inside the `./src/...` folder. There is a PLACEHOLDER.js inside the container folder, since i didn't have any Container yet.

Styles are placed in the `styles` folder inside the `./src/...`folder.

## Misc

Since i made this repo just for myself and i don't want to publish any NodeJS apps right now, i probably won't change the `npm build` command.
However, of course you are free to implement your own build configs, etc. This repo exist to have a very basic and open boilerplate to extend.