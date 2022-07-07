# e-comm

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
- Download 
    - package.json (npm init -y)
    - package-lock.json and node modules (npm i)
    - express (npm i express)
    - dotenv (npm i dotenv)
    - mysql2 (npm i mysql2)
    - sequelize (npm i sequelize)
- Create a .env file and put in your username and password. Also add the DB_NAME which is ecommerce_db (will be found in db file under schema.sql)
- Open Work Bench and put in lines found in schema and run it by clicking on the lightning bolt 
- open server.js in terminal, then type " node seeds/index.js " in order to populate database 
- Now that database is populated, run your server in terminal (node server.js)
- Open Insomnia in order to GET, POST, PUT, DELETE: Categories, Tags and Products. 
- Make sure that text is in JSON 
    - CATEGORIES 
        - GET ALL: http://localhost:3001/api/categories
        - GET BY ID: http://localhost:3001/api/categories/1 (input any id between 1-5)
        - POST: http://localhost:3001/api/categories 
            - EX:
              {

                "category_name": "Socks"

                }
        - DELETE: http://localhost:3001/api/categories/6 (input any id between 1-5) 
        - PUT: http://localhost:3001/api/categories/2 (input any id between 1-5)
    - TAGS
        - GET ALL: http://localhost:3001/api/tags
        - GET BY ID: http://localhost:3001/api/tags/1 (input any id between 1-8)
        - POST: http://localhost:3001/api/tags 
            - EX: 
              {

                "tag_name": "Computer"

                }
        - DELETE: http://localhost:3001/api/tags/9 (input any id between 1-8)
        - PUT: http://localhost:3001/api/tags/10 (input any id between 1-8)
    - PRODUCTS
        - GET ALL: http://localhost:3001/api/products
        - GET BY ID: http://localhost:3001/api/products/1 (input any id between 1-5)
        - POST: http://localhost:3001/api/products 
            - EX: 
                 {

                    "product_name": "Soccer Ball",
                     "price": 200.00,
                    "stock": 3,
                    "tagIds": [10]

                }
        - DELETE: http://localhost:3001/api/products/4 (input any id between 1-5)
        - PUT: http://localhost:3001/api/products/5 (input any id between 1-5)

## Links 
GitHub: https://github.com/MaSaLo13/e-comm

Walkthrough Video: https://drive.google.com/file/d/1-0EdxTHIwQIen18HXoKMbZY80l_CN8Of/view
