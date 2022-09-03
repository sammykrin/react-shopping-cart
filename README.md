# React Shopping Cart 

1. Create React App

2. Project Development Workflow
    1. Create Google Spreadsheet
    2. Add columns Feature, Description, State, and Duration
    3. Enter Product Component, show list f product, and open, 2
    4. Add Time ? Hours, Rate 30 USD/Hours, cost ? USD
    5. Add All Features
    6. Create Github account
    7. Create new repository
    8. Add it as remote repository in VS Code
    9. Commit changes on github
    10. Push changes on github
    11. Start => create new feature Feature 1 in google spreadsheet
    12. Create a new branch feature-1 for testing the workflow
    13. Add "// branch feature-1 in App.js line 1
    14. commit with message "feature 1"
    15. Click publish changes
    16. Open respository page on github
    17.  Create pull request 
    18. Merge pull request .

3. Cart Component
    1. Set active task management spreadsheet
    2. Create branch cart-component
    3. Product.js
    4. Handle "Add To Cart" to this.props.addToCart(product)
    5. App.js
    6. Add cartItems to state as []
    7. Create addToCart(product)
    8. Slice, Check product existance, add to cartItems
    9. Cart.js
    10. Define cartItems, order from this.props
    11. Check cartItems.length and show message
    12. List cartItems {cartItems.length > 0 &&}
    13. index.css
    14. Style cart, cart-header, cart-items (img, li)
    15. Use localStorage on App constructor to load cart items (JSON.parse)
    16. Use LocalStorage on addToCart to save cart items (JSON.stringify)

4.  Checkout Form
    1. Set active task spreadsheet
    2. Create branch checkout-form 
    3. Cart.js  
    4. Make cart items persistent
    5. Use LocalStorage on App constructor to load cart  items (JSON.parse)
    6. Use localstorage on addCart to save cart item (JSON.stringify)
    7. Handle click n process
    8. Update showCheckOut state to true on click 
    9. Conditional rendering Checkout form 
    10. Get Email, Name, and Address required input 
    11. Define handleInput function 
    12. Add checkout button 
    13. Handle onSubmit form Event by this.createOrder
    14. Create order object and pass to parent to handle it 
    15. Publish changes
    16. Pull request, merge, change to master
    17. Task management spreadsheet set it done

5.  Add Modal and Animation
    1. Set active task management spreedsheet
    2. Cretate branch animation-modal 
    3. Show animation
    4. Install react-reveal 
    5. Create fade effect from bottom for products
    6. Create fade left for add to cart 
    7. Create fade right for show checkout form 
    8. Open modal by click on prodcut image
    9. Install react-modal
    10. Products.js 
    11. Import modal
    12. Set state for prodcut to null 
    13. Define openModal and closeModal 
    14. Show Modal if product exist
    15. Create Modal
    16. Create Modal
    17. Index.css
    18. Style product details 
    19. Commit and publish changes
    20. Pull request, merge, change to master
    21. Task management spreedsheet set it to done.

6.  Create Product Backend
    1. Install nodemon globally
    2. Add server.js 
    3. Install express body-parser mongoose shortid
    4. Install MongoDB
    5. app = express()
    6. app.use(bodyParser.Json())
    7. mongoose.connect()
    8. create product model
    9. app.post("/api/products")
    10. Postman send post request
    11. route.get("/api/products")
    12. route.delete("/api/products/:id")

7.  Add Redux
    1. What is redux?
    2. Uodate task on spreedsheet
    3. create branch add-redux-products 
    4. npm install redux react-redux redux-thunk
    5. create types
    6. types.js
    7. define FETCH_PRODUCTS
    8. actions/productActions.js
    9. declare fetchProducts
    10. create reducers
    11. reducers/productReducers.js
    12. define case FETCH_PRODUCTS
    13. create store
    14. store.js
    15. import redux
    16. set initial state
    17. define initialState
    18. create store
    19. import productReducers
    20. combine reducers
    21. use store
    22. App.js
    23. import store
    24. wrap all in provider
    25. connect producers
    26. components/producer.js
    27. connect to store
    28. import fetchProducts
    29. set state products to null
    30. fetch products from did Mount
    31. package.json
    32. set proxy to http://127.0.0.1:5000
    33. npm run server
    34. check products lsit 
    35. commit and publish 
    36. send pull request and merge
    37. update spreedsheet