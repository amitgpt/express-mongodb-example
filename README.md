# express-mongodb-example

# RESTful API with Node.js, Express.js, Mongoose and MongoDB.


Example of a RESTful API built with Node.js, Express.js, Mongoose and MongoDB.

## RESTful API endpoints
## GET `/api/products`

Get all items.

+ Method: `GET`
+ URL: `/api/products`


### POST `/api/products`

Create a new products.

+ Method: `POST`
+ URL: `/api/products`
+ Body:

`js
{
	"title":"Product_Name",
	"price":"500",
	"instock":"true",
	"photo":"null"
}
`

### GET `/api/products/:products`

Get item with specific id.

+ Method: `GET`
+ URL: `/api/products/product_id`


### PUT `/api/products/:product_id`

Update entire item with specific id.

+ Method: `PUT`
+ URL: `/api/products/product_id`
+ Body:
`js
{
	"title":"Product_Name",
	"price":"500",
	"instock":"true",
	"photo":"null"
}
`


### DELETE /api/product/:product_id

Delete item with specific id.

+ Method: `DELETE`
+ URL: `/api/product/product_id`

## Install

	npm install


# Run
0. Make sure MongoDB is running.
1. `nodemon index.js`

 
