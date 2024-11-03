## User Directory Express App

#### Commands

##### Starting app

`$ npm start`

##### Verifying app

`$ curl http://localhost:3000`

##### Listing all users

`curl --location 'http://localhost:3000/users' --data ''`

##### Adding user

`curl --location 'http://localhost:3000/users' --header 'Content-Type: application/json' --data '{"userId": "bob"}'`
