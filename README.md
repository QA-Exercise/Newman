# SDET Postman/Newman skills check

### Goal

Using this API - https://dummyapi.io/ - create your own collection of requests with tests. Ensure that you cover the important endpoints and edge cases.

Docs: https://dummyapi.io/docs

### Getting started
Run `npm install`
Run `npm test` to run Newman on the current collection

### Instructions

1. Fork this repo to your own **PRIVATE** repository. This should not be public.
1. Import `Dummy API.postman_collection.json` into Postman. It has a sample request (including API key) and test in it to get you started.
1. Update the collection with your own tests
1. Export to the repo under the same name as the original, OR update nodejs.yml to use the URL of your collection
1. Run your collection locally with `npm test`
1. Push to your forked repo & ensure that the Github Action passes with all of your tests.
1. Under your repo settings -> collaborators, grant Read access to @QA-Exercise.

### What we look for

* Depth > breadth for this exercise. Your tests should cover the happy paths as well as real edge cases. You don't need to automate every single endpoint available.
* Readability > volume. Make your tests easy to understand and maintain.
* Variation > repetition. Don't test GETs only - test some of each CRUD operation.
