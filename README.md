# Figma Plugin Starter

## Full instructions: 

https://www.figma.com/plugin-docs/plugin-quickstart-guide/

If you're new to Figma plugins, it might be a good idea to use their Quickstart Guide, at the link above. If the plugin architecture is familiar to you, and you just want a faster setup, clone this repo and go!

## Install Node & TypeScript (if you haven't already):

Install Node.js: 

https://nodejs.org/en/download/

Install TypeScript (globally):

`npm install -g typescript`

## Getting started 

1. Clone this repo
2. Change the plugin name in your manifest.json file
3. Change the plugin name & description in your package.json file
4. Install stuff 👇🏼

Install all dev dependencies, & create your package-lock.json:

`npm install` 

Get the latest type definitions for the plugin API:

`npm install --save-dev @figma/plugin-typings`

To compile TypeScript to JavaScript, and watch for changes while working:

`npm run watch`