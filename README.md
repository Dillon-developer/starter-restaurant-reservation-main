# Final Capstone: Restaurant Reservation System
-----------------------------------------------------------------------------------------------
### Live Link 
-----------------------------------------------------------------------------------------------
Reservation App Link

-----------------------------------------------------------------------------------------------
## Application Summary:

This application was made with restaurant staff in mind. The main functions of the application include: creating, editing, searching, and canceling reservations. The search function of the application can find current reservations through the phone number or name of the customer. The application keeps track of how many seats are available and who is occupying each table. 


-----------------------------------------------------------------------------------------------
## Screenshots
-----------------------------------------------------------------------------------------------
DASHBOARD

![image](https://user-images.githubusercontent.com/72090865/116441764-5a70fb00-a817-11eb-9bde-d514169697a2.png)

RESERVATION FORM

![image](https://user-images.githubusercontent.com/72090865/116441692-47f6c180-a817-11eb-90bc-231fd3a45d22.png)



-----------------------------------------------------------------------------------------------------
## STACK

This app was developed using JavaScript, React, Express, Node, PostgreSQL, KnexJS, HTML, CSS, and BootStrap.

-----------------------------------------------------------------------------------------------------

## API Documentation:

![image](https://user-images.githubusercontent.com/72090865/116443219-ff400800-a818-11eb-8454-81e4a1117bbd.png)

-----------------------------------------------------------------------------------------------------

## Reservation JSON Example

```js
{
 "reservation_id": 1,
 "first_name": "Frank",
 "last_name": "Palicky",
 "mobile_number": "202-555-0153",
 "reservation_date": "2020-12-30",
 "reservation_time": "20:00",
 "people": 1,
 "created_at": "2020-12-10T08:31:32.326Z",
 "updated_at": "2020-12-10T08:31:32.326Z"
}
```

-----------------------------------------------------------------------------------------------------

## Table JSON Example

```js
{
 "table_id": 2,
 "table_name": "#2",
 "capacity": 6,
 "occupied": false,
 "reservation_id": null
}
```


-----------------------------------------------------------------------------------------------------

## How to start it up:

Install dependencies in terminal with

```js
npm install
```

Start server 

```js
npm start
```

Lastly you will create a database to store all the reservation data. This will require a .env file:

```js
// back-end .env example -> Connects to database
DATABASE_URL=enter-your-production-database-url-here
DATABASE_URL_DEVELOPMENT=enter-your-development-database-url-here
DATABASE_URL_TEST=enter-your-test-database-url-here
DATABASE_URL_PREVIEW=enter-your-preview-database-url-here
LOG_LEVEL=info

// front-end .env example -> Connects to server
REACT_APP_API_BASE_URL=http://localhost:5000
```


























