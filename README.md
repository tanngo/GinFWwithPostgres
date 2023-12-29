This is the sample Golang Rest with jWT login and register using Gin Framework and Postgres

Sample register:
curl --location 'http://localhost:8000/users/signup' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer <<JWT>>' \
--data-raw '{
    "first_name":"ngo",
    "last_name":"nguyen",
    "email":"tanngontn@gmail.com",
    "password":"123456",
    "phone":"123456789",
    "user_type":"ADMIN"
}'

Sample login
curl --location 'http://localhost:8000/users/login' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer <<JWT>>' \
--data-raw '{
    "email":"tanngontn@gmail.com",
    "password":"123456"
}'
