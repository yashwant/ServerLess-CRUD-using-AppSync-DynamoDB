# AWS AppSync APIs (with DynamoDb as DataSource)
(This is simple CRUD operation implementation. There is no authentication / authorization implemented)
## Steps to deploy the code
1) Configure AWS environment credentials on local machine 
2) Clone the code
3) Rename config/parameters.template to config/parameters.yml
4) Do npm install (Make sure node 8+ is installed on the machine)
5) Run sls deploy

## Testing Deployed Code
Go to AppSync Console and look for instructions to integrate with your App in iOs/Android/Javascript

You can also test the APIs by running queries in AppSync Console
To test via Appsync console, you can use test data from test-data folder

## AppSync APIs

User
- Add User
- Get User by Id
- Update User
- Delete User

User Login History
- Add Login History
- Get Login History
