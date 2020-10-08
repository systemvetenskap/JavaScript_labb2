## Getting started
In this exersice you are going to modify the DOM using JavaScript. This repo contains an index.html file, and an app.js file. Please note that node.js and git are pre-requisits for following the below instructions.  

1. Clone this repo
2. Change into the directory you just cloned, so that your terminal is in the same directory as the package.json file
3. Install dependencies by typing `npm install` 

Your webbrowser is not allowed to access the file system, for security reasons. Therefore loading the JS module won't work without a web server. Fear not! One is included in the package.json as a development dependency.

4. In the directory where the package.json is located, type `npm run dev`. Your local development server should start and give ouput similar to below:

```
Starting up http-server, serving src
Available on:
  http://127.0.0.1:8081
  http://192.168.1.180:8081
Hit CTRL-C to stop the server
```

Open 'http://127.0.0.1:8081 in Google Chrome, and you should see the exersice instructions. 
Open Chrome Devtools, and switch to the console tab. You should see 'js loaded!' printed to the console. You're then good to go. 

If you have problems with http-server starting, try installing it as a global npm package: `npm install -g http-server`

## Exersice Instructions
The exersice instructions are included directly in the index.html & app.js files.

Please keep in mind, that you will need to refresh your browser, after you've made JS changes, for these to take effect, as the JS script is only loaded once on page load.


## Submitting your lab assignment
You submit your assignment by pushing your work to your own, public, github repo (or, private, which you share with Lars/Erik). In the top right corner of github, click the + then new repository. Or, visit (https://github.com/new)[https://github.com/new]. Choose a name for your repo, select public, do not check boxes to add things. Click create repository. Then copy the link to your new repository. It should look something like https://github.com/yourUsername/repoNameYouChose.git .

Then in the command line, where your project is, issue the following commands:

```
git add .
git commit -m 'index html file changes on load as instructed!'
git remote remove origin
git remote add https://github.com/yourUsername/repoNameYouChose.git 
git push -u origin main
```
Refresh the page with the repo you created, and you should see your code pushed. 





