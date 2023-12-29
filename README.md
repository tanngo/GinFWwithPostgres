This is the sample Golang Rest with jWT login and register using Gin Framework and Postgres

Sample register:
curl --location 'http://localhost:8000/auth/register' \
--header 'Content-Type: application/json' \
--data '{"username":"ngonguyen", "password":"ngonguyen"}'

Sample login
curl --location 'http://localhost:8000/auth/login' \
--header 'Content-Type: application/json' \
--data '{"username":"ngonguyen", "password":"ngonguyen"}'
