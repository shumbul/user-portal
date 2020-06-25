#User Portal Using AngularJS
##Requirements
1. Nodejs 
(install from: https://nodejs.org/en/) <br>
2. Any text editor (preferably Atom or Sublime Text or Visual Studio) <br>
3. AngularJS
(Link: https://ajax.googleapis.com/ajax/libs/angularjs/1.8.0/angular.min.js) <br>
4. Github account (https://github.com/) <br>
5. Git Bash (download from: https://gitforwindows.org/) <br> <br>

##Steps to run
1. Chech whether the following above requirements are fulfilled properly in your OS, run the following commands in Command Promt:<br>
a. ```>node --version <br>```
b. ```>npm --version``` <br>
c.	i) ```>npm i browser-sync@2.24.1``` <br>
	ii) ```>browser-sync version ```<br>
d. ```>git --version``` <br>
<br>
2. Upload the Angular file on your github account and copy clone link <br><br>
3. Open git bash and run the commands: <br>
```$ git clone <clone_link>```  <br>
```$ cd <filename> ```<br>
**NOTE: if your setup is working, you should be able to run all the commands of step-1 on git bash**<br><br>

4. Run: <br>
```$ browser-sync --server --directory --files "**/*/" ````<br><br>
5. If the setup is fine, you should see the "localhost " link on the screen, go to the link and open index.html file. <br><br>
6. Register your details and Login using the registered username and password. <br>
