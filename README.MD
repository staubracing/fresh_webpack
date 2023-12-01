### so try this
run `yarn` to install dependencies.

Run `yarn build` and and open the index.html file.  This should work and render the app.

Comment out the import statement in the app.js file and run `yarn build` and open the index.html file see that it fails.  For me it renders nothing.

Look at the console and see the error: `Uncaught TypeError: Cannot read property 'call' of undefined`

