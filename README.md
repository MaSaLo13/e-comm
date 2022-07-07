# E-COMMERCE BACK END

## Description
Build a back end for an e-commerce website in order to be able to compete with other e-commerce companies.  
The back end includes API routes for Categories, Products and Tags: 
- GET 
- POST 
- PUT 
- DELETE 

## Installation 
- Git Clone repository 
- Open file in VS Code 
- Create a .env file and put in your username and password. Also add the DB_NAME which is ecommerce_db (will be found in db file under schema.sql)
- Watch Walktrough Video for on how to invoke e-commerce back end
- The following are links for Categories, Tags and Products: 
    - CATEGORIES 
        - GET ALL: http://localhost:3001/api/categories
        - GET BY ID: http://localhost:3001/api/categories/1 (input any id between 1-5)
        - POST: http://localhost:3001/api/categories 
            - EX:
                {

                    "category_name": "Socks"

                }
        - DELETE: http://localhost:3001/api/categories/5 (input any id between 1-5) 
        - PUT: http://localhost:3001/api/categories/2 (input any id between 1-5)
            - EX: 
                {

	                "category_name": "Laptop"

                }
    - TAGS
        - GET ALL: http://localhost:3001/api/tags
        - GET BY ID: http://localhost:3001/api/tags/1 (input any id between 1-8)
        - POST: http://localhost:3001/api/tags 
            - EX: 
                {

                    "tag_name": "Computer"

                }
        - DELETE: http://localhost:3001/api/tags/8 (input any id between 1-8)
        - PUT: http://localhost:3001/api/tags/7 (input any id between 1-8)
            - EX: 
                {

	                "tag_name": "Laptops"

                }
    - PRODUCTS
        - GET ALL: http://localhost:3001/api/products
        - GET BY ID: http://localhost:3001/api/products/1 (input any id between 1-5)
        - POST: http://localhost:3001/api/products 
            - EX: 
                 {

                    "product_name": "Soccer Ball",
                    "price": 200.00,
                    "stock": 3,
                    "tagIds": [1, 2, 3, 4]

                 }
        - DELETE: http://localhost:3001/api/products/4 (input any id between 1-5)
        - PUT: http://localhost:3001/api/products/5 (input any id between 1-5)
            - EX: 
                {

                    "product_name": "BasketBall",
                    "price": 100.00,
                    "stock": 5,
                    "tagIds": [1, 2, 3]
   
                }

## Links 
GitHub: https://github.com/MaSaLo13/e-comm

Walkthrough Video: https://drive.google.com/file/d/1YPPnfL1Iw7BDa1hyWs1HdK2vDIrFVabS/view
