# protractor-example
Example repo using protractor

## setup

`npm install`

## running the tests

Update and start selenium server

```bash
npm run wdm -- update 
npm run wdm -- start --detach # --detach to run in background
```

Run the tests

`npm test`

When you are done with tests, end the server process

`npm run wdm -- shutdown`
