
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

Serverless should be installed globally via NPM (currently 1.0.0. rc) - see`` ~\scripts\1_InitialiseProject.bat``
(all cli commands are assumed to be executed from project root)

Assuming you are happy to start with the code as is - you just need to instal the already defined dependecies.
To install the dependencies run:
```
>> npm install
```

SERVERLESS_ADMIN_AWS_PROFILE=MyCredsProfile