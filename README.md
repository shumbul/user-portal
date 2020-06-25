#User Portal Using AngularJS
##Requirements
1. NodeJs
(install from: https://nodejs.org/en/) <br>
2. Any text editor (preferably Atom or Sublime Text or Visual Studio) <br>
3. AngularJS
(Link: https://ajax.googleapis.com/ajax/libs/angularjs/1.8.0/angular.min.js) <br>
4. Github account (https://github.com/) <br>
5. Git Bash (download from: https://gitforwindows.org/) <br>

##Steps to run
1. Chech whether the following above requirements are fulfilled properly in your OS, run the following commands in Command Promt:
a. node --version
b. npm --version
c.	i) npm i browser-sync@2.24.1
	ii) browser-sync version
d. git --version
<br>
2. Upload the Angular file on your github account and copy clone link
3. Open git bash and run the commands:
$ git clone <clone_link> 
$ cd <filename> <br>
4. Run:
$ browser-sync --server --directory --files "**/*/"
5. If the setup is fine, you should see the "localhost " link on the screen, go to the link and open index.html file.
6. Register your details and Login using the registered username and password.
