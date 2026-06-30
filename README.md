# Automating API Test Flow
CRUD functions

## Collections Included
'Mini Project 2- Automating API Test Flow.json` - Main API collection
Has 4 APIs:
1. Login API after which token is generated & then extracted & stored in token variable
2. Create User API: Using the extracted token in Authorization & create a new user. UserID is fetched from response & stored in UserID variable
3. Update user API: Using the UserID fetched from Create User API, created user is updated
4. Delete User API: Created user is deleted by passing the UserID

## How to Use
1. Import `Mini Project 2- Automating API Test Flow.json` into Postman
2. Set environment variables:
baseUrl : https://reqres.in
Job: QA Engineer
Name: Shiva
UserId
runStartTime
token
4. Run the requests

## API Base URL
`https://reqres.in`
User needs to have a account in the above URL. After account is created, user will get a API Key which will be required to use the APIs.
Pass this API key in headers for all APIs as 
x-api-key: <YOUR API KEY>
