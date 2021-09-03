# Inventory-Management-System
Function print_Sales():
   Prints the Sales JSON File
Function print_product(dic):
   Takes dictionary of Inventory as input and prints all the items in list
    
Function updatestock(dic):    
   Takes dictionary of Inventory as input .
   Then user have to input what he wants to change
        1. Add/Remove stock: You can add or reduce number of products.(*If number entered to reduce the              stock is greater than the actual quantity of product then it will be set to 0.)
        2. Change Price: Input new value of product
        3. Exit
        Calls Function Updaterecord(dic) to update the Inventory
    
        
Function purchase(dic):
    Takes dictionary of Inventory as input .
    Then user have to input Product ID and Quantity:
    If entered Quantity is greater than actual Quantity Output is:Insufficient Quantity
    Else Cost is calculated and Quantity mentioned is reduced from the stock.
    Cost is displayed to the user and Inventory and Sales JSON is updated
    

Function Updaterecord(dic):
    Takes dictionary of Inventory as input .
    Opens Records.json in write mode and updates it with dictionary of Inventory
    

Function Updatesales(name,cost,q,time):
    Takes Name,Cost,Quantity and Time of Purchase as input .
    Opens Sales.json in write mode and updates it with Name,Cost,Quantity and Time of Purchase.
   
    
Function Addrecord(dic):
    Takes dictionary of Inventory as input .
    Then user input Product Name, Quantity and Price
    Update the record of inventory with new Item.

Main Function:
Header File used:-from IPython.display import clear_output,JSON
Output Menu:
  Welcome !!!

   Menu
   1. Make purchase
   2. View Inventory
   3. Add Product
   4. View Sales
   5. Update Product details
   6. Exit
Based On Input Respective Function is called.
Menu continues till user doesn't want to continue.
clear_output() *Used To clear previous Output 
    
    
  
