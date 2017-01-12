#basic-gulp-setup
This sets up a very basic outline for an app that will use 
gulp and browser-sync to watch the index.html and .scss
files and auto inject or refresh the web page on change.

Files are contained in the app/ folder with two subdirectories
for /css and scss/. css/ will be updated by gulp when the
scss is saved. The index.html file is in the app/ and is the
start point for the app.

##Setup
$ npm install gulp gulp-sass run-sequence browser-sync --save-dev

This installs all the necessary node modules and updates the
package.json's devDependencies.

##Running
$ gulp

This starts the watching and should open up a new browser tab
with your current page.