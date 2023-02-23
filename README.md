
# Basic User Listing
List all users Laravel API


## API Reference

#### Get all users

```http
  GET /api/user
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|     Null  |  Null    | Null                       |


## Documentation

git clone https://github.com/webitpradip/basic-api-user-list.git

create a database in mysql

copy .env.example file as .env

write down your mysql datbase name and password in .env file


open console inside the folder basic-api-user-list

RUN php artisan migrate

RUN php artisan db:seed

RUN php artisan serve


Now test the api in postman

http://127.0.0.1:8000/api/user




