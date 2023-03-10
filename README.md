Download and import to Postman
---
These api tests check the basic business logic of applications (smoke tests):

1.Create

2.Read

3.Update

4.Delete

---


To run with CLI(git bash):

npm install -g newman 

For Open_Api: 

newman run Open_API_testing.postman_collection.json -e Open_API_Enviroment.postman_environment.json

For Users_Api:
