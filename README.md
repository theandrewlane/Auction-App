# [Auctions-Near-Me](http://auctions-near-me.herokuapp.com/)

[![Build Status](https://travis-ci.org/theandrewlane/Auction-App.svg?branch=master)](https://travis-ci.org/theandrewlane/Auction-App)
[![Gitter](https://badges.gitter.im/theandrewlane/Auction-App.svg)](https://gitter.im/theandrewlane/Auction-App?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Heroku](https://camo.githubusercontent.com/be46aee4f8d55e322c3e7db60ea23a4deb5427c9/68747470733a2f2f6865726f6b752d62616467652e6865726f6b756170702e636f6d2f3f6170703d6865726f6b752d6261646765)](http://auctions-near-me.herokuapp.com/)

#### [Project Proposal](./docs/Project-Proposal.pdf)
### TODOs
- Come up with a name for this application
  - Also update the repository name
- Create Gulp [EC2 deploy task](http://docs.aws.amazon.com/codedeploy/latest/userguide/github-integ-tutorial.html)
- [EC2 Setup](https://scotch.io/tutorials/deploying-a-mean-app-to-amazon-ec2-part-1)


<hr>
<hr>
## Before You Begin
Before you begin we recommend you read about the basic building blocks that assemble a MEAN.JS application:
* MongoDB - Go through [MongoDB Official Website](http://mongodb.org/) and proceed to their [Official Manual](http://docs.mongodb.org/manual/), which should help you understand NoSQL and MongoDB better.
* Express - The best way to understand express is through its [Official Website](http://expressjs.com/), which has a [Getting Started](http://expressjs.com/starter/installing.html) guide, as well as an [ExpressJS](http://expressjs.com/en/guide/routing.html) guide for general express topics. You can also go through this [StackOverflow Thread](http://stackoverflow.com/questions/8144214/learning-express-for-node-js) for more resources.
* AngularJS - Angular's [Official Website](http://angularjs.org/) is a great starting point. You can also use [Thinkster Popular Guide](http://www.thinkster.io/), and [Egghead Videos](https://egghead.io/).
* Node.js - Start by going through [Node.js Official Website](http://nodejs.org/) and this [StackOverflow Thread](http://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js), which should get you going with the Node.js platform in no time.


## Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
  * Node v5 IS NOT SUPPORTED AT THIS TIME! 
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).
* Ruby - [Download & Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)
* Bower - You're going to use the [Bower Package Manager](http://bower.io/) to manage your front-end packages. Make sure you've installed Node.js and npm first, then install bower globally using npm:
*_OR_*
* Docker

```bash
$ npm install -g bower
```

* Sass - You're going to use [Sass](http://sass-lang.com/) to compile CSS during your grunt task. Make sure you have ruby installed, and then install Sass using gem install:

```bash
$ gem install sass
```

* Gulp - You may use Gulp for Live Reload, Linting, and SASS or LESS.

```bash
$ npm install gulp -g
```

* All other dependencies - This installs all node modules specified in ```package.json```

```bash
$ npm install
```


## Docker Development 
### If you have trouble installing the dependencies, create and utilize the docker container
- (TODO) push docker image to docker hub

- Build the Docker container:
```bash
$ docker build -t auctions-near-me .
```
- Run the Container
```bash
$ docker run -it auctions-near-me
```

## Development
### After installing all dependencies, use Gulp to build, lint, and serve.
### ```gulp dev``` will automatically rebuild and serve when you've made code changes

- Run the Gulp dev task (should be left running while developing)
```bash
$ gulp dev
```
