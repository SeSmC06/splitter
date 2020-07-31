To run this application...

**\***SETUP**\*\***
-If you do not have Node.js on your machine, please go to https://nodejs.org/en/download/ to download and install node.js
-node version v10.16.0 was used

**\***Run Application Locally**\*\***

1. Navigate into the location of splitter folder
2. Open up the terminal from inside the splitter folder (or you can navigate to this directory from the terminal)
3. In terminal, cd into splitter
4. Run 'yarn start' command in the terminal. This will have the Express.js server up and running
5. 'yarn test' command in terminal for local test

```
To use the API with curl or postman
Submit a GET request to http://localhost:8000/pyramid
Format it was a raw JSON request body

{
  "input": "valid pyramid string"
}

Note String is valid if it contains alphabets and spaces, everything else would return 400 message
```

**\***NOTES**\*\***

Packages used:
-expressjs
-node version v10.16.0
