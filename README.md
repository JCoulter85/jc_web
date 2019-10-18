# James Coulter

## Welcome to the jc_web README

Welcome to my personal website.

To get started there are a few things that you will need in order for you to build the web app.

Please go to github.com and install git as well as make your own github account:

[Github link here](http://github.com/)

After installing git:

Please find a specific folder you would like to place the web application and run these following commands within the CMD:

- $ `git init`

- $ `git clone (https://github.com/JCoulter85/jc_web.git)`

This will pull all the files needed for the web application.

From here you will need to also clone the json-server in a separate folder location. Here is the command to clone the server:

`git clone (https://github.com/JCoulter85/jc_web_server.git)`

## Installing what you will need to run both the server & the web application

After you clone both the web application and the server you will need to install:

- $ `Node.js`

- $ `NPM`

Install Node.js and NPM to your local machine by visiting the website provided:

[Node.js & NPM link here](https://nodejs.org)

You can check that node.js & npm have been installed by checking their versions by running these commands in your CMD:

- $ `node -v`

- $ `npm -v`

After node.js & npm are installed on your machine you will need to run these commands in your CMD:

- $ `Angular CLI v6.2.1`

- $ `Angular Materials v6.4.7`

- $ `Angular CDK v6.4.7`

- $ `Angular Animations v6.1.7`

- $ `Hammerjs v2.0.8`

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

## Running jc_Web

Running web application:

- $ `ng serve`

Navigate to http://localhost:4200/ The app will automatically reload if you change any of the source files.

## Deploy the server

- Locate and visit the servers location on your local machine in your CMD

Run:

- $ `json-server --watch db.json -d 2000`

The content within the server has necessary contecnt for the web application.

## Code scaffolding

Run:

- $ `ng generate component component-name`

This will generate a new component. You can also use

- $ `ng generate directive|pipe|service|class|guard|interface|enum|module`

## Build

Run:

- $ `ng build`

This will build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running end-to-end tests

Run:

- $ `ng e2e`

This will execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use:

- $ `ng help`

Or you can visit the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
