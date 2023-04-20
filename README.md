# J.A.T.E. - Just Another Text Editor
  
![badge](https://img.shields.io/badge/license-MIT-blue.svg)

## Description
This application takes an existing text editor app and adds functionality for it to work as a PWA and function offline. This application is deployed through Heroku.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Table of Contents
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Deployed Link](#deployed-link)
- [Demo](#demo)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation
`git clone` the repo to your local machine. To use this application, run the following command to install the dependencies: 

     npm install

Then run the following command:

`npm run start:dev`

## Usage
Type the following command in your termimal:

`npm run start`

Then open Insomnia and type http://localhost:3000/ to run this application on your local machine.

## Deployed Link

The link to the deployed application is: //.


## Demo
Below is the demostration of this application. Please click <a href="#">here</a> for walk-through video.



## License
This application is licensed under MIT license. 


## Tests
To run tests on the application, run

`npm install jest`

and then `npm run test` from the command line.


## Questions
For any question, please contact me on GitHub: [HarryWard-15](https://github.com/HarryWard-15) or email me at hward.1508@gmail.com.


