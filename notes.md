GET /register
- sign up form

POST /users
- create user in db with validation

GET /login
- present login form
POST /login
- create session and redirect

GET /titans/new
- show form to create new post of Titan sighting
- enter name, date, location, type, status

POST /titans
- take post request data and save it to db

GET /titans
- show list of all titan entries

GET /titans/:id
- show details of titan entry

PATCH /titans/:id