# Welcome to the jc_web README

Welcome to my personal website.

To get started there are a few things that you will need in order for you to build the web app.

Please go to <http://github.com> and install git as well as make your own github account:

[Github link here](http://github.com/)

After installing git:

Please find a specific folder you would like to place the web application and run these following commands within the CMD:

- $ `git clone https://github.com/JCoulter85/jc_web.git`

This will pull all the files needed for the web application.

## Installing what you will need to run both the server & the web application

After you clone both the web application and the server you will need to install `Node.js` and `NPM` to your local machine. Visit the website provided and install:

[Node.js & NPM link here](https://nodejs.org)

You can check that `node.js` & `npm` have been installed by checking their versions by running these commands in your CMD:

- $ `node -v`

- $ `npm -v`

Next will will have to install Angular & all of the Agular items. Please run these commands in your CMD:

- $ `Angular CLI v6.2.1`

- $ `Angular Materials v6.4.7`

- $ `Angular CDK v6.4.7`

- $ `Angular Animations v6.1.7`

- $ `Hammerjs v2.0.8`

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

## Running jc_web

Now that we are ready to run the web application, There are two ways to do so. Option one is for web dev and option two is to view the website through the as is json-server. If you want to just view the web app please use option 2 as it is much easier.

### Option 1

This require the `json-server` to be deployed in order for some contect to be loaded. In the CMD direct yourself to the `json-server` folder within the `JC_Web` folder. Once in the `json-server` folder, you can run this command:

- $ `json-server --watch db.json -d 2000`

After the `json-server` has been deployed, you can now serve the web app. Open another CMD terminal and open the `JC_Web` folder. Once within the `JC_Web` folder you can run this command:

- $ `ng serve`

You now can visit the link below to view the web application.

<http://localhost:4200>

### Option 2

In the CMD direct yourself to the `json-server` folder within the `JC_Web` folder. Once in the `json-server` folder, run this command:

- $ `json-server --watch db.json -d 2000`

You can now view the web application via the link below:

- <http://localhost:3000/>

## Updating json-server content

If you edit the web app you will also have to update the `json-server` for deployment. Once you are ready to update the server you will need to run this command in the JC_Web folder in the CMD:

- $ `ng build --prod`

This will create the information in the `JC_Web\dist` folder that will need to copy and pasted into the `json-server\public` folder. This will update all the old content and bring the web app up to date. *Kind of important so please do not forget to do so.*

## Optional Commands

Below this point are a list of commands that are unnecessary to view the web application but are available if you choose to use them.

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
