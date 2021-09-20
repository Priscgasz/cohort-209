NOTE : "$" sign only means => instruction to input in a terminal window (you MUST omit the $) 

## VS Studio Code

A very nice text editor : ) (not the only alternative though)

- recommended extensions:
  - prettier
  - ES7 React/Redux/GraphQL/React-Native

## for windows users ONLY

I recommend skipping WSL (ubuntu virtual machine) if you are NOT interested in digging into Linux now.
For most users, a  super simple approach would be git for windows : https://gitforwindows.org/
Leave everything by default during installation.
Right click in any folder and choose "git bash here" : you'll get a unix-like terminal window !


## nodejs

Check the installed node version in a terminal with the following command :
$ node -v

The current recommended version is 14.17.6 (LTS => Long Term Support).
Any version above 10 will be okay for this course.
Take your time and follow official nodejs install procedure for your OS :
https://nodejs.org/en/download/package-manager/

then install the lite-server library globally on your machine :

https://www.npmjs.com/package/lite-server

$ npm install -g lite-server
OR if on mac/linux 
$ sudo npm install -g lite-server


## mongodb

Take your time and follow official mongodb install procedure for your OS :
https://docs.mongodb.com/manual/installation/
While installing, choose to install compass as well


