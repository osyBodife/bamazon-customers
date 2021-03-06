## bamazon-customer
The App is a Node.js application designed to help users select product they want to buy.
The Following technologies were used to develop the Application
1. Mysql as database
2. Node.js
3. Dependencies include;
    1. npm modules
    2. npm inquirer module
    
    !["Image"](assets/images/dependencies_db_connection.png "db connection")
   
## Currently the Application has two modules, as follows;
1. Customer Module
   1. This was designed to enable a customer buy things from the App
   2. It can be accessed from node using bamazoncustomers.js
2. Manager Module
   1. This module is accessed through bamazonManager.js file
   2. It was designed to enable the Manager add inventory, pull reports , add new products to the store etc

### Sample of Transaction Activities
# Customer Module
a. The Store prompts the user to select product based on what is available on DB

!["Image"](assets/images/customer_prompt_select_product_01.png "customer prompt image")

b. customers makes a selection of a product with ID of 3
!["Image"](assets/images/customer_select_03.png "customer makes a selection")

c. Purchase Confirmed and Db updated
!["Image"](assets/images/purchase_confirmed.png "purchase confirmed")

d. Cost of Purchase Computed and displayed
<br>
!["Image"](assets/images/cost_of_purchase.png "cost of purchase confirmed")

e. Customer selects more quantity than is available in db
<br>
!["Image"](assets/images/insufficient_qty.png "insufficient quantity")

f. Updating Transactions in the Database
<br>
  i. image 1 Database Bafore the transaction
  <br>
  !["Image"](assets/images/database_before.jpg "database before")
  <br>
  ii. image 2 Database after the transaction
  <br>
  !["Image"](assets/images/database_after.jpg "database after")
  <br>
 
  ## Manager Module  
  ### Manager Acivity Options
  
!["Image"](assets/images/manager_module_options.png "manager options")
1. View Products on Sale
<img src="assets/images/manager_module_view_products_onsale.png" atl="view products">

2. View Low Inventory
<img src="assets/images/manager_module_view_low_inventory.png" atl="view low inventory">
3. Add to Inventory( this will update stock position)
<img src="assets/images/manager_module_add_inventory.png" atl="inventory module">
4. Add New Product Module
<img src="assets/images/manager_add_new_product_module.png" atl="add new product">
 i. Initiate Operation
 <img src="assets/images/manager_add_operation_01.png" atl="add operation">
 ii Add New Product Db complete View
<img src="assets/images/manager_add_operation_db_complete_view.png" atl="add db view">

