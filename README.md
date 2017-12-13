# AWS amplify & React example

## Getting started

### clone & setup

```
$ git clone git@github.com:hideokamoto/aws-amplify-react-example.git
$ npm install or yarn install
```

### update AWS info

```
$ vim src/App.js
Amplify.configure({
    Auth: {
        identityPoolId: 'XX-XXXX-X:XXXXXXXX-XXXX-1234-abcd-1234567890ab', //REQUIRED - Amazon Cognito Identity Pool ID
        region: 'XX-XXXX-X', // REQUIRED - Amazon Cognito Region
        userPoolId: 'XX-XXXX-X_abcd1234', //OPTIONAL - Amazon Cognito User Pool ID
        userPoolWebClientId: 'XX-XXXX-X_abcd1234', //OPTIONAL - Amazon Cognito Web Client ID
    }
});
```

### Run as local

```
$ npm strat or yarn start
```
