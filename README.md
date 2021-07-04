# screen-recorder
Sample electron-forge app to capture the screen

I copied it from a sample at:-
https://codingshiksha.com/javascript/build-a-screen-recorder-desktop-app-using-electron-forge-node-js-full-project/

and got it working with the latest electron and node js

To use it you need to first clone it and then npm init it to download the various things

the command line to initialise things is npx create-electron-app screen-recorder

The repository already has most of what you need but im not sure if you need to create the app first.

to run it type npm start

The broswer has the web tools loaded for debugging.  To stop this comment out line 25 of index.js

Note the webPreferences in the CreateWindow decleration in index.js.  They are required by the later versions of nodejs

