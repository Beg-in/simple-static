# begin-simple
Build simple websites right, faster.

## What begin-simple does
* Runs a simple server with live changes as you code
* On-the-fly, live prepping of files for production:
  * [Pug](https://pugjs.org/) support (.pug -> .html)
  * [Sass](https://sass-lang.com/) support (.sass & .scss -> .css)
  * Minifies .js and .html files
* Bundles in [Frow CSS](https://frowcss.com) framework (optional)
* Bundles in [letsGo JS](https://letsgojs.com) framework (optional)
* Enables easy to manage JS libraries via src/scripts/_templates.txt
* Builds everything into /docs for instant deployment via [GitHub Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#publishing-your-github-pages-site-from-a-docs-folder-on-your-master-branch)
* Works on Mac, Linux, and Cloud9

## Set up for Mac/Linux
* Fork this [begin-simple repo](https://github.com/Beg-in/begin-simple) and clone it to computer
* Navigate to this project via Terminal
* Ensure you have a recent version of [Node.js](https://nodejs.org/)
* Run `npm install`

## Set up for Cloud9
* Fork and then clone this [begin-simple repo](https://github.com/Beg-in/begin-simple) into Cloud9 (as Blank Template).
* Run `nvm install node && nvm alias default node && nvm use node`
* Run `npm install`

## Customize for your project
* Add 'docs' to the .gitignore file if you do not plan on using GitHub Pages for hosting
* Customize package.json and LICENSE
* Visit src/scripts/_includes.txt to add libraries or disable letsGo.js
* Visit src/styles/styles.sass to add more styles or disable Frow CSS
* Search all files for "replace-me"

## Using begin-simple
* Navigate to project via Terminal
* Run `npm start`
* Watch terminal for the link to preview your website
