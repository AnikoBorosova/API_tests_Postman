## API_tests_Postman

- unit testing
- e2e-testing
- contract testing

API tested: https://petstore.swagger.io/

### Versions, requirements

- Tested on Ubuntu v20.4
- Node v14.17.0
- newman v5.3.0
- Postman app

### How to run the tests

- Clone the repo
- Run `npm install`
- Run `newman run Petstore.postman_collection.json` or `npm test`

### Postman features used

- pre-request scripts
- environment variables - store secrets/tokens
- collection variables - set, get, unset variables
- saving responses
- store custom test snippets on collection-scope
- schema validation with `tv4`