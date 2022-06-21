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