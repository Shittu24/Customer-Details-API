# Customer Relation Management API With GO

## Introduction

This is a simple Customer Relation API built with Go with sqlite database where you can create, delete, update and get a customer's complete information.

##### Do the stuff below to initialize your project

1. Clone the repository
   `git clone https://github.com/Shittu24/Customer-Details-API.git`
2. Change the directory
   `cd Customer-Details-API`
3. Get all the dependencies
   `go mod tidy`
4. Run your project
   `go run main.go`

5. After you've built the project, these are the queries to interact with the API on Postman -

#### Get All Leads

To get all customer's information - http://localhost:3000/api/v1/lead GET

#### Get Specific Lead

To get a particular customer's information - http://localhost:3000/api/v1/lead/:id GET

#### Create Lead

To create a new customer's information - http://localhost:3000/api/v1/lead/ POST

#### Delete Lead

To delete a particular customer's information - http://localhost:3000/api/v1/lead/:id DELETE
