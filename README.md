#MERN eCommerce

1. Products List
    1. create products array
    2. add products images
    3. render products
    4. products style

2. Add Routing
    1. npm i react-router-dom
    2. create route for home screen
    3. create router for product screen

3. Create Node.JS Server
    1. run npm init in root folder
    2. UPdate package.json set type: module
    3. Add .js to imnports
    4. npm install express
    5. create server.js
    6. add start command as node backend/server.js
    7. require express
    8. create route for / return backend is ready
    9. move products.js from frontend to backend
    10. create route for /api/products
    11. return products
    12. run npm start

4. Fetch Products From Backend
    1. set proxy in package.json
    2. npm install axios
    3. use state hook
    4. use effect hook
    5. use reducer hook

5. Manage State By Reducer Hook
    1. define reducer
    2. update fetch data
    3. get state from usReducer

6. Add bootstrap UI Framework
    1. npm install react-bootstrap bootstrap
    2. update App.js
    3. add footer

7. Create Product and Rating Component
    1. create Rating component
    2. create Product component
    3. Use Rating component in Product component

8. Create Product Details Screen
    1. fetch product from backend
    2. create 3 column for image, info and action