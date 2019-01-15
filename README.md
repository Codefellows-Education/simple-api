![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## HTTP and REST Documentation

### Author: Lena Eivy

### Links and Resources
* [repo](https://github.com/applena/11-http-and-rest)
* [simple-api repo](https://github.com/applena/simple-api)

### Setup
#### `.env` requirements
* `PORT` - localhost:3000

#### Running the app
* `npm setup && npm start`

* in a new terminal, run httpie against it:
* ex. `http :3000/categories`
* ex. `http :3000/products`
* ex. `http :3000/products/:id`
* ex. `http :3000/categories/:id`

## data model
* `categories`
  * `_id`, `name`, `display_name`, `description`
* `products`
  * `_id`, `category`, `name`, `display_name`, `description`
  
## endpoints
* `/categories`  GET, POST
* `/categories/:id/` PUT, DELETE
* `/products`  GET, POST
* `/products/:id/` PUT, DELETE

