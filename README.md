To begin, we need to load the data to the Mongo Database.
===
Step1
==
Make sure you have MongoDb installed and you have the DB running, if not, go to the terminal and type 
```console
    > mongod
```

Step2
==
Clone, install packages
```console
    > git clone https://github.com/GeorgeFourikis/DataChallenge.git
    > cd DataChallenge
    > npm i
```

Step3
==
We now need to load the data coming from the JSON file to our Mongo Database, so we run the command below
```console
    > node ./loadDB.js
```

Step4
==
To run the application with nodemon you can type

```console
    > npm run-script watch
```

To run it simply using node

```console
    > npm start
```

Step5
==
Go to localhost:3000, enjoy! :)