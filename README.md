# Requirements
- make sure your PORT 3000 is free
- [Insomnia]https://insomnia.rest/products/insomnia or [Postman]https://www.postman.com/, Needed to test the API !
- open a terminal
```sh
npm i
```

# Implemented
 - Adding trips POST - localhost:3000/trip
 - List the trips GET - localhost:3000/trips
 - Add an expense POST - localhost:3000/expense
 - List all expenses GET - localhost:3000/expenses

 # Examples
 - POST TRIP
```json
    {
        "name":"First Trip"
    }
```
- POST EXPENSE
```json
    {
        "trip":"612d065fbd5cd53735c3745e",
        "date":"2021-08-31T10:40",
        "amount": 50,
        "category":"food",
        "description":"Lunch on the road"
    }
```

## _Congrats_

