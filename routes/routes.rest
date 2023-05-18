POST http://localhost:3000/api/sign-up
Content-Type: application/json

{
  "username": "tester3",
  "password": "123456",
  "password_repeat": "123456"
}

###

POST http://localhost:3000/api/login
Content-Type: application/json

{
  "username": "tester3",
  "password": "123456"
}

###

GET http://localhost:3000/api/secret-route
Authorization: Bearer eyhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6IkxvcmVueiIsInVzZXJJZCI6IjFhODNiZGFiLTJmNDYtNGJhNC05MjJmLTkyYWRiYTI5ODk4NCIsImlhdCI6MTY4NDM5MDUzOCwiZXhwIjoxNjg0OTk1MzM4fQ.YjM-W3dk7XaqHXX2ZgVj2v94UWrNEuRyEh0mTpE5NFA