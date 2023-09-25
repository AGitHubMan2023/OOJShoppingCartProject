# OOJShoppingCartProject
This project is are Class Project For OOJ 

This is our use Case :D

Use Cases
Use Case: Log In
1.User enters username and password in the text boxes
2.Systems takes input and checks if the entered data matches with the saved login information and if the user is a customer or seller.
3.Information is correct and the system logs the user in, opening the window displaying the list of products.

Variation Wrong Log In 
3.1. Information is incorrect. System displays “Incorrect username and/or password” message on window
Back to Step 1.

Use Case: Customer Adds Items to Shopping Cart
1.Customer follows steps of Log in as a Customer
2. Customer types an item for the System to find in the search bar.
3.System displays a page of items to the user .
4.Customer Selects first Item presented under results
5.System Pulls Item Info
6.Customer Clicks add to cart
7.System adds Item to the cart

Variation No Item Found
1.1  Following from step 2 the user types an item to find in the search bar.
1.2  System takes input and checks the data to search store inventory, but fails
1.3 System Prints "Item not found"
1.4. Return to Step 2

Use Case: Customer Reviews Product Details
1. Customer carries out Log In as verified Customer
2. Customer types an item in the search bar for the system to find.
3. System displays the item
4. Customer clicks on the item
5. System displays a pop up window/ or in current window containing the product and the details

Use Case: Customer Reviews/Updates Shopping Cart
1. The Customer Adds Items to Shopping Cart as verified Customer
2. The Customer Clicks on the Shopping Cart Icon
3. The System displays current Contents of shopping cart
4. The Customer can Review Items, Update the Quantity, Remove items, or continue to check out
5. The Total is recalculated.

Use Case: Customer Checks Out
Customer carries out Review/Update shopping cart as verified Customer
Customer clicks on the check out button.
System displays a receipt showing the items, their price, quantity, and the total amount due.
Customer clicks Pay button and pays
System displays form details for Customer to enter his/her card details. After details are entered, Customer clicks the “Pay” button. 
System displays a “Thank you for your purchase” message. In the backend, the quantity of the items decreases by how much the customer bought.
Customer can either close the app or click on the home button taking him/her back to product screen

Use Case: Seller Reviews/Updates Inventory
Seller carries out Log In as verified Seller
System gets the inventory management page
Seller review the existing products, quantities, and the current set prices.
Seller can update the inventory by modifying the existing products, like changing the selling price, product name etc.

Use Case: Seller Adds New Product
1. Seller carries out Reviews/Updates Inventory as verified seller
2. Seller clicks on the “Add Product” button.
3. System displays the new product fields. 
4. Seller enters the new product details such as the product name, selling price, invoice price, and quantity.
5 Seller commits new product details to the system
6. System auto generates the product ID to assign to the new product.

Use Case: Seller Reviews Sales Data
1. Seller carries out Log In as verified Seller
2. Seller would click on the Sales Tab
3. The system will get the Sales Page
4. The Seller will review Sales data such as Profits, Costs, Profits, and Payment Information

User Case: New User
1. In the System Login Page User Selects New User Option
2. System loads the New Account page displaying the form for User to enter email, username, password and account type, either Customer or Seller.
3. User enters Email, User Name, password information, and selects the account type.
4. System Verifies Valid username, Email, and Password.
5. System brings up Payment information
6. User Enters Payment Information 
7. System Verifies Valid Payment information
8. User Clicks Create Account to submit information
9. The System Creates the new account.

-Credit to
Brandon Hyppolite
Atheek Ashkar
Manny Jimenez 
