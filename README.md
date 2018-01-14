# express-mongodb-example

RESTful API with Node.js, Express.js, Mongoose and MongoDB.

Example of a RESTful API built with Node.js, Express.js, Mongoose and MongoDB.

RESTful API endpoints
GET /api/products
Get all products.

Method: GET
URL: /api/products
POST /api/products
Create a new products.

Method: POST
URL: /api/products
Body:
{
	"title":"Product_Name",
	"price":"500",
	"instock":"true",
	"photo":"null"
}
GET /api/products/:products
Get item with specific id.

Method: GET
URL: /api/products/product_id
PUT /api/products/:product_id
Update entire item with specific id.

Method: PUT
URL: /api/products/product_id
Body:
{
	"title":"Product_Name",
	"price":"500",
	"instock":"true",
	"photo":"null"
}


Method: PATCH
URL: /api/items/1
Body:
{
  "quantity": "30"
}
DELETE /api/product/:product_id
Delete item with specific id.

Method: DELETE
URL: /api/product/product_id
Install
npm install

Run
Make sure MongoDB is running, if not: sudo ~/mongodb/bin/mongod (assuming you have ~/mongodb directory).
nodemon index.js

 
