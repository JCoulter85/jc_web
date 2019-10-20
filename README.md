# Welcome to the jc_web README

Welcome to my personal website.

To get started there are a few things that you will need in order to build the web application.

Please visit <https://git-scm.com/downloads> and install `Git` as well as visiting the link below to create your own `github` account:

[Github link here](http://github.com/)

After installing `git`, please find a specific location / folder in your CMD where you would like to place the web application. Once there, run this command:

- $ `git clone https://github.com/JCoulter85/jc_web.git`

This will pull the files needed to build the website.

If you are new to `Git` do not worry!!! Here is a fantastic cheat sheet with tons of commands and what they do!!!

[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## Installing what you will need to run both the server & the web application

After cloning the project you will need to install `node.js` and `npm`. Visit the website provided and download \ install:

[Node.js & NPM link here](https://nodejs.org)

Checking the verisons of both `node.js` & `npm` will indicate that they were installed to your machine. Run these commands:

- $ `node -v`

- $ `npm -v`

Next, install Angular & all of the Angular items. Run these commands:

- $ `npm init`

- $ `npm install Angular CLI v6.2.1`

- $ `npm install Angular Materials v6.4.7`

- $ `npm install Angular Animations v6.1.7`

- $ `npm install --save @angular/flex-layout@6.0.0-beta.18`

- $ `npm install font-awesome@4.7.0 --save`

- $ `npm install Hammerjs v2.0.8`

- $ `npm install lite-server --save-dev`

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

## Running jc_web

Congratulations, you are now ready to run the web application. There are two ways to view the site: **Option One** is for developers. **Option Two** is for the user who would like to just view the web app as a visitor. If you want to just view the web app, please use option 2 as it is much easier.

### Option 1

This requires the `json-server` to be deployed for contect to be loaded while working on the project. In your CMD, direct yourself to the `json-server` folder within the `JC_Web` folder. ( _`JC_Web\json-server`_ ) Once in the `json-server` folder, run this command:

- $ `json-server --watch db.json -d 2000`

After the `json-server` has been deployed, you can now serve the web app for a live feed. Open a new CMD terminal and direct yourself to the `JC_Web` folder. Once within the `JC_Web` folder, run this command:

- $ `ng serve`

You now can visit the web app via the link below:

<http://localhost:4200>

### Option 2

In the CMD direct yourself to the `json-server` folder ( _`JC_Web\json-server`_ ). Once within the `json-server` folder, run this command:

- $ `json-server --watch db.json -d 2000`

You can now view the web application via the link below:

- <http://localhost:3000/>

Keep in mind, if you change the website via an editor, the content will not update with this option.

## Updating json-server content

If you edit the web application you will also have to update the contents within the `json-server` for deployment. Once you are ready to update the server, you will need to run this command in the `JC_Web` folder via the CMD:

- $ `ng build --prod`

This will create new information in the `JC_Web\dist\jc_web` folder. These new files will need to be copied and placed into the `JC_Web\json-server\public` folder. ( _Remember that the server folder is within the `JC_Web` folder_) This will update the old content and bring the web app up to date. **This is important. Do not forget this step.**

## Optional Commands

Below are optional commands.

### Code scaffolding

Run:

- $ `ng generate component component-name`

This will generate a new component. You can also use:

- $ `ng generate directive|pipe|service|class|guard|interface|enum|module`

### Build

Run:

- $ `ng build`

This will build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running end-to-end tests

Run:

- $ `ng e2e`

This will execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use:

- $ `ng help`

Or you can visit the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
