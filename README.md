## How to implement

### frontend:

1- npx create-react-app react-google-login
2- npm install react-google-login
3- Edit App.js
4- create h1 for app name
5- define loginData state hook
6- check loginData and render content
7- if loginData is null render Google Login component
8- if loginData isn't null render you are logged in message 
9- implement handleLogout
10- implement handleFailure
11- implement handleLogin

### google cloud platform

1- login to google
2- go to https://console.cloud.google.com
3- create a project
4- go to api service credentiel
5- accept consent screen
6- create oauth client Id
7- create .env file and save it as REACT_APP_GOOGLE_CLIENT_ID
