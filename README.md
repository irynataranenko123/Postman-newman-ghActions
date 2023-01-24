# Postman + newman + github actions (Simple store template)

## The API was tested in this project. Collections were taken from the <a href="https://github.com/WannaBeDream/Postman-newman-ghActions" /> repository </a>

```
In this project:
1. Made several integration tests in Postman for the store.collection.json
2. Added Github action to run petstore.collection.json in Github pages
```
## Technologies
```
- Node.js: 18.12.1
- Postman: 10.8.0
```
## Setup 
To run this project, install it locally:
```
$ git clone https://github.com/PepesSpi123/Postman-newman-ghActions
$ npm install
```
## Running test:
To run tests in command line and create a report: 
```
$ npm run test-and-report
```
To run tests in Postman:
```
1. Run npm run tern-on-api in comand line
2. Open Postman application or Postman <a href="https://web.postman.co" /> web Postman </a>
2. Import store.collection.json 
3. Click the button "Runner"
4. Drag the folder "store" into the "Run order" field
5. Press the button "Run store" 
```
## Report:
``` 
When you use 'npm run test-and-report' the report is saved in the docs folder as an html file
```
## GitHub Pages:
Automatic report deployment implemented to GitHub Pages:
```
https://pepesspi123.github.io/Postman-newman-ghActions/
```


