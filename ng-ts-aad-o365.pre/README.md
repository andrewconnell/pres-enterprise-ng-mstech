In order to run the completed project provided here, you must perform some setup steps. 

## Prerequisites to Complete this Example
1. You must have an Office 365 tenant . 
1. You must have an Azure subscription with the Office 365 tenant's directory tied to the Azure subscription.
1. You must have [node.js](http://nodejs.org/) installed on your development environment. You can get node.js from the [downlods](http://nodejs.org/download/) section on their site. Certain [node.js packages](https://www.npmjs.org) available via [NPM](htttps://www.npmjs.org) will be used in creating this Office App.
1. You will need a text editor for this lab... anything will do from [Visual Studio](https://www.visualstudio.com/) or [Visual Studio Code](http://code.visualstudio.com) to [Brackets](http://www.brackets.io) to [WebStorm](https://www.jetbrains.com/webstorm/) to Notepad.

## Create a SharePoint Site using the Provided Site Template
Create a new SharePoint site in SharePoint Online using the template found within the [ExpenseApp.wsp](ExpenseApp.wsp) file.

Take note of the URL of the site.

## Download all NPM & Bower Packages
Download all NPM packages (used to build & self-host the project) and bower packages (used for external 3rd party script libraries).

````
$ npm install
````

> The command `npm install` will also execute `bower install` to download all bower packages.