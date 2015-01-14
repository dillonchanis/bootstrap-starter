Bootstrap Starter
=================

A basic, responsive, Bootstrap 3.0 template-building environment.. Most likely production ready. The ultimate goal of this project is to create a fairly snappy, bulletproof template-authoring environment with some of my favorite stuff.

##Getting Started

###The Wussy Way
1. Just Download the Master Zip, and work with whatever resides in the bootstrap starter folder that contains `index.html`, I'll try and keep it up to date, and tidy enough to just dump somewhere and edit. Bootstrap is Vanilla, Javascript and CSS is minified however.. So you may want to get your hands dirty.

###The Way Way
1. Visit https://help.github.com/articles/set-up-git/ for information on setting up Git.
2. Download the Git client (for [Mac](https://windows.github.com/) OR for [Windows](https://windows.github.com/) )
3. You're going to get your hands dirty in the command line and install:
  1. Node.js ([nodejs.org/](http://nodejs.org/))
  2. NPM (which comes with Node.js, but visit [www.npmjs.org](https://www.npmjs.org/) for more information)
  3. Bower (installed using NPM, see [bower.io](http://bower.io/))
  4. Grunt (installed using NPM, see [gruntjs.com](http://gruntjs.com/getting-started))
4. `cd` to the bootstrap-starter directory and enter the following command to install all the dependencies and the whatnot: ``` npm install ``` This runs through the `package.json` file and installs all the dependencies this project requires. 
5. To build out you'll want to run grunt, you can either run: ``` grunt build -v ``` OR ``` grunt -v ``` Grunt runs verbose (clueing you into the errors and the whatnot). A `watch` task will refresh your page/s as you edit (uses `liveReload.js`, install __[http://livereload.com/](the appropriate extension for your browser)__, you'll thank me later) if you're set up for the correct port (`liveReload` uses 35729 by default): `localhost:35729/index.html`. 
6. That's it! Do your worst and customize this thing out, if you do things __the Way Way__ you can:
* Customize Bootstrap via `bootstrap-starter/sass/style.scss` (be sure to read the comments, not all variables should be edited)
* Extend Bootstrap and create your own classes using SASS (examples can be found in `style.scss`)
* Quickly develop you're own production ready (I hope) templates and HTML

##Optional
__Bower__ is optional... The components that come with the latest version of this thing should be kept up to date as I work through this thing and get through the kinks. You can update them yourself `cd`-ing to the root folder for this project and running:
``` bash
bower install
```

##To-Do
- [x] Organize dependancies into production-ready directories using Grunt and whatever Tasks might be needed to automate
- [x] Add Autoprefixer to build process for Bootstrap CSS
- [ ] Flesh out the SASS components to do some things with sprites etc
- [ ] Fork the Dev branch of this repo (on my to-do list) for shared access and staging to Master
- [ ] Add optional versions of index.html, fixed and static header, sidebars, thumbnail grids, common UI etc.
- [ ] Declare production-ready, ducks row in, t's crossed i's dotted
