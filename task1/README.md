### Node.js Task1

We are now going to prepare your development environment in Node.js.

Node.js uses [npm](https://www.npmjs.com) to manage programming projects consisting of its
dependencies, build and install processes along with general project information and requirements.

Setup your environment by cloning the [bootstrap](https://bitbucket.org/uniqdevs/node-boilerplate) repository.
Inside you will find a package.json file, which dictates how your environment will be configured.

Run ```npm install```. It will pull all the required dependencies.

You should now build your first application. Open an index file (src/app.js by default) and use a function called ```main```
to print out a string ```Hello, world!``` to console (stdout).

Build your project with ```npm test``` 
(this command is a convenience command that runs ```npm run-script build && npm test```).

If everything went well, you should now have a built and transpiled code in the ```dist``` directory.

Now run ```npm start``` and check if you get ```Hello, world!``` printed out.
