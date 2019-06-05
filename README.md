# runscope-to-postman

# Runscope-to-Postman [![Build Status](https://travis-ci.org/postmanlabs/runscope-to-postman.svg?branch=master)](https://travis-ci.org/postmanlabs/runscope-to-postman)

Convert Runscope Radar Tests to Postman Collection v2

## Description

## Running the Tool

```
npm test
```

Currently, the core functionality of the tool is based in the test feature.
The `index.js` file is imported into a Mocha test script, then executed using the Mocha CLI.
Aims for the next iteration are to refactor this to have its own functionality, with potential tests running against it separately.

## Authors

* [Abhijit Kane](https://github.com/abhijitkane) of [Postman Labs](https://github.com/postmanlabs) - Original work, core functionality
* [Henry Raschke](https://github.com/jebrii) of [Altair Engineering](https://github.com/altairengineering) - ES6 Refactor, changes to architecture
