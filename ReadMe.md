
You will need Node and NPM installed

The project is ready to roll, however if you wanted to start from fresh you will need to create the package .json file (which defines your dependencies) use
```
npm init --yes
```
I have updated the author info manually and added dependencies eg
```
npm install eslint --save-dev
```
You would need to do this for each dependencies you want.

I have set up an eslint config file:
```
./node_modules/.bin/eslint --init
```

Serverless should be installed globally via NPM (all cli commands are assumed to be executed from project root)

Assuming you are happy to start with the code as is - you just need to instal the already defined dependecies.
To install the dependencies run:
```
>> npm install
```

Set you AWS credtial profile to be used (ie change from my serverless-rhystest_dev profile to whatever profile you are using, or leave it out if you are using the default)
```
Serverless deploy
```

If you want - set up lambci as per : https://github.com/lambci/lambci
You will need slack and git tokens to proceed with this.