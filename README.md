# daledger
DA Ledger Blockchain MarketPlace for Architects in Romania
=======
Instructions for how to install and run the code (windows):

1. To view the github repo go to:

`https://github.com/euroledger/daledger`

2. clone the code (important: always work on test branch)

`git clone -b test https://github.com/euroledger/daledger.git`

`cd daledger\server`

3. Install server node modules

`npm install`

4. Install client node modules (on dev there are two processes running concurrently: expressjs and react client)

`cd client`
`npm install` 

5. Create the file dev.js in server\config and paste in the dev keys (ask Mike).
These are our private keys for various APIs such as Google and MongoDB which are not committed to github for security reasons.

6. Run the app

`npm run dev`

This concurrently runs the server and client (see package.json)

# To change branch in git
`git checkout master`
`git checkout test`

# To commit to test branch

`git push -u origin test`

# To merge test -> master

`git checkout master`
`git merge test`
`git push origin master`
>>>>>>> 4c47dc9b21fc32dc2cbfda5cbde061bd2f56a479
