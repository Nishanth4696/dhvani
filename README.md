# iGene_edge Dashboard
> A Dashboard built with the MERN stack .

MERN stack is intended to provide a starting point for building full-stack JavaScript applications, including dynamic web and mobile apps. The stack is made of Mongo, Express, React and NodeJS.
<p align="center">
   <a href="https://travis-ci.com/amazingandyyy/mern">
      <img src="https://travis-ci.com/amazingandyyy/mern.svg?branch=master" />
   </a>
   <a href="https://github.com/amazingandyyy/mern/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-green.svg" />
   </a>
   <a href="https://circleci.com/gh/amazingandyyy/mern">
      <img src="https://circleci.com/gh/amazingandyyy/mern.svg?style=svg" />
   </a>
</p>

# Usage (Run Fullstack app on your machine)

## Prerequisites
- [MySql](https://github.com/mysql)
- [Node](https://nodejs.org/en/download/) ^13.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

```
To install Nodejs & NPM:
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

notice, you need client and server runs concurrently in different terminal session, in order to make them talk to each other


## Project Structure
```terminal
LICENSE
package.json
server/
   app/ // where all server side component located
   server.js
   package.json

client/
   src/
      Components/
   App.js
   Index.js
   package.json
...
```

## Client-side usage(PORT: 3000)
```terminal
$ cd client   // go to client folder
$ npm install       // npm install packages
$ npm start // run it locally

// deployment for client app
$ npm run build // this will compile the react code using webpack and generate a folder called docs in the root level
$ npm run start // this will run the files in docs, this behavior is exactly the same how gh-pages will run your static site
```

## Server-side usage(PORT: 8081)

### Prepare your secret

run the script at the first level:

(You need to add your own secret and access keys and db details on .env to run these app)


### Start

```terminal
$ cd server   // go to server folder
$ npm install       // npm install packages
$ npm start // run it locally
$ npm run build // this will build the server code to es5 js codes and generate a dist file
```


# Screenshots of this project
## For User
User have to Select Item for Inspection
![User visit public and Home page](https://igenie365-my.sharepoint.com/:u:/r/personal/nishanth_kr_igenie_ai/_layouts/15/Doc.aspx?sourcedoc=%7B57d07c70-3a56-4f27-8764-8379624ddeb4%7D&action=embedview)

Inspection Page
![User can sign in or sign up](https://www.linkpicture.com/q/Screenshot-from-2022-02-04-16-27-19.png)

Calibrate Page where you can check whether the camera is working fine
![After signing in user can go to account route](https://www.linkpicture.com/q/Screenshot-from-2022-02-04-16-27-11-1.png)

Report Page where you can see the details of the Item and its status
![After signing in user can go to account route](https://www.linkpicture.com/q/Screenshot-from-2022-02-04-16-36-50.png)

## For Admin
Admin have access to user managemnt page where he can create users and manage them
![create users](https://www.linkpicture.com/q/Screenshot-from-2022-02-04-16-17-44.png)
