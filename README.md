# GO-ECOMMERCE

This project is an ecommerce backend service which could be used by seller to be able to store the details of their product, pricing, quantities, descriptions and so many more.

With the perfect frontend framework, this backend would prove it self to be outstanding with the blazing fast Golang web framework [GIN], it aims to deliver the best.

It is really simple to set up and to follow through.

## HOW TO SET UP
- git clone this repo
        `https://github.com/Lawsonredeye/go-ecommerce.git`
- create a .env file with the following details added.
```
# USE A MYSQL DB CREDENTIAL
# BUT YOU COULD USE POSTGRES TOO BUT YOU WOULD NEED TO TWEAK THE SETTINGS AT THE model/db.go
HOST=YOUR_DB_USERNAME
HOST_PASSWORD=YOUR_DB_PASSWORD
DB_NAME=go_ecommerce_db

# JWT SECRET KEY
SECRET_KEY=USE_ANY_SECRET_KEY_OF_YOUR_CHOICE
```
- Next run the command `go mod tidy` to install all packages && libraries used in the project
- run `go run .`
