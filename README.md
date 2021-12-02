# API test automation using <span style="color:yellow">newman</span>

    Newman is a CLI Collection Runner for Postman. It is built with extensibility in mind so that you can 
    easily integrate it with your continuous integration servers and build systems.
 

## AHS Postman Public Workspace
For executing test cases in AHS project manually using Postman follow this link to our [Postman public workspace](https://www.postman.com/akvelonhr/workspace/ahs-api)

# Getting started

### 1. Newman is built on Node.js. To run Newman, make sure you have Node.js installed.
#### You can [download and install](https://nodejs.org/en/download/current/) Node.js on Linux, Windows, and macOS.

### 2. After you install Node.js, Newman is just a command away. Install Newman from npm globally on your system, which allows you to run it from anywhere.
    $ sudo npm install -g newman

### 2.1. If npm packages 'looking for funding', try to turn it off globally:
    $ npm config set fund false --global 

### 3. The easiest way to run Newman is to run it with a collection.
#### For that go to parent directory, where is collection and environment files placed: 
    $ cd newman/execution/

### <span style="color:yellow">For executing tests</span>
    $ newman run QA_AHS_collection.json -e AHS_env_loc.json

### Execution results:
![Results](https://github.com/kadirovgm/newman/blob/master/media/result.png)

# How to integrate to CI?
#### [How to Build a CI/CD Pipeline that Executes API Tests](https://dev.to/leading-edje/hello-newman-how-to-build-a-ci-cd-pipeline-that-executes-api-tests-2h5l)

# For more information
### [newman official documentation](https://www.npmjs.com/package/newman)
### [Running Postman collections with newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/)
