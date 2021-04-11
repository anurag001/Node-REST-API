# Node-REST-API
1. Run -> npm install
2. Run -> nodemon server.js
3. Use POST req to create user: http://localhost:3000/users/register
4. Use POST req for login with authentication:  http://localhost:3000/users/authenticate
It will generate jwt token which we have to use for the below requests
5. Use Get req to fetch userList: http://localhost:3000/users/userList/firstName/Ravi
6. Use Get req to fetch userList along with pagination; http://localhost:3000/users/userList/firstName/Ravi/2

Refer snapshots for the payloads in the same folder
