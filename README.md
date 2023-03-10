Download and import to Postman

---


To run with CLI(git bash):

npm install -g newman 

For Open_Api: 

newman run Open_API_testing.postman_collection.json -e Open_API_Enviroment.postman_environment.json

For Users_Api:

newman run users_bugred.postman_collection.json -e users_bugred.postman_environment.json

