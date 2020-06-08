# 2020-bc-testme
Custom testing framework

Setup:
1) add #!/usr/bin/env node to top on index.js file

2) npm init -y

2) add "bin": { "testme": "index.js" } to package.json

4) at terminal in proj dir run npm link

5) type testme at command line anywhere on machine to run!!!

------------

To run test with Mocha: (npm install mocha -g)
1) cd sampleProject
2) type mocha in terminal

------------

REGEX:

//g

/\n/g  -> find all new line 

replace with new line and two tabs

\n\t\t

const message = err.message.replace(/\n/g, '\n\t\t');

------------



