# jest-bug

Run `npm install` to install dependencies.

Run `./node_modules/.bin/jest ./test.js` to run the Jest test script, it will print out 'top-level', which is the exported value from `dir.js`.

Run `node ./test-node.js` to run the script in vanilla Node.js. It will print out 'nested', which means Jest's `require()` is incompatible with Node.js'
