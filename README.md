# API test automation using <span style="color:yellow">newman</span>

    Newman is a CLI Collection Runner for Postman. It is built with extensibility in mind so that you can easily integrate it with your continuous integration servers and build systems.

#### In this README file you can find instructions for executing newman. 

## AHS Postman Public Workspace
For executing test cases in AHS project manually using Postman follow this link to our [Postman public workspace](https://www.postman.com/akvelonhr/workspace/ahs-api)

# Getting started

### Newman is built on Node.js. To run Newman, make sure you have Node.js installed.
#### You can [download and install](https://nodejs.org/en/download/current/) Node.js on Linux, Windows, and macOS.

### After you install Node.js, Newman is just a command away. Install Newman from npm globally on your system, which allows you to run it from anywhere.
    $ npm install -g newman

### The easiest way to run Newman is to run it with a collection.
#### For that go to parent directory, where is collection and environment files placed: 
    $ cd newman/execution/

### <span style="color:yellow">For executing tests</span>
    $ newman run QA_collection.json -e AHS2.env.json

# For more information
### [newman official documentation](https://www.npmjs.com/package/newman)
### [Running Postman collections with newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/)