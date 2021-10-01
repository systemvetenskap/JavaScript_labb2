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

If you have problems with http-server starting, try installing it as a global npm package: `npm install -g http-server`. Then, with your terminal path in the src folder within this repo, type http-server. 

## Exersice Instructions
The exersice instructions are included directly in the index.html & app.js files.

Please keep in mind, that you will need to refresh your browser, after you've made JS changes, for these to take effect, as the JS script is only loaded once on page load.


## Submitting your lab assignment
This assignment is for your eyes only. You don't have to share your solutions. However, for your own sake. Save and push the code to GitHub.


```
git add .
git commit -m 'index html file changes on load as instructed!'
git remote remove origin
git remote add https://github.com/yourUsername/repoNameYouChose.git 
git push -u origin main
```
Refresh the page with the repo you created, and you should see your code pushed. 
