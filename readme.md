# API - Testing using POSTMAN

## Postman

Postman is an [API platform](https://www.postman.com/api-platform/) for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.

More: [Read here](https://www.postman.com/product/what-is-postman/)

## Newman

Newman is a command-line collection runner for Postman. It allows you to effortlessly run and test a Postman collection directly from the command-line. It is built with extensibility in mind so that you can easily integrate it with your continuous integration servers and build systems.

#### Installing Newman

1. Newman is built on Node.js. To run Newman, make sure you have Node.js installed. Follow the [steps to download Node](https://nodejs.org/en/download/package-manager/) for your CI's platform. (Note that some CI systems have configurations that pre-install Node.) Ensure you are using Node.js v4 or above.
2. Install Newman from npm globally on your system, which allows you to run it from anywhere:

```bash
$ npm install -g newman
```


### newman-reporter-htmlextra


A [Newman](https://github.com/postmanlabs/newman) HTML reporter that has been extended to include the separation of the iteration runs so these are no longer aggregated together and also some additional `handlebars helpers` to enable users to create better custom templates.

This reporter comes with a dashboard style summary landing page and a set of different tabs which contain the detailed request information. There are also a few optional configuration flags available, to tailor the final report in a number of different ways.

To `globally` install the `htmlextra` package:

```
npm install -g newman-reporter-htmlextra
```
