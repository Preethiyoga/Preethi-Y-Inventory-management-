# ETG-IMS-Preethi-Y
#
# Files attached:
###  *report.txt -> contains menu of the item
###  *sales.txt -> contains details about transactions made
###  *code(editable from google colab)
# Attributes of the items  in report.txt:
###   * product id
###      *name
###      *Price
###      *Rating
###      *cus_ct(Count of the customers whoever rated the product
###      *Dicount_percentage
###      *Items Available(QUANTITY of the item in stock)
###      *Material Composition
# Attributes of the transaction in sales.txt:
##    *sales(this will have the count of the transaction made ,from which I can get the transaction ID for upcoming transactions)
##    *Initially the transaction count is 5
###           *Product(Has an array of product id's of the purchased products)
###           *Product Name(Has an array of the product name of the purchased products )
###           *Time (has the date day and time of the transaction )
###           *Price(Has the transacted amount)
#         
# At first you have to give an input :
# (Functionalities):
##    '1': to add an item to the report.txt
###                * can add more no. of items to the eisting product
###                * can add new product to the report.txt
##    '2': To purchase an item
###            You can purchase an item which is available in the report.txt
###            it will modify the sales.txt 
####                  *By incrementing 'sales'-count of the transaction
####                  *append the deatils of new transcation at the end
####                  *Transaction_id of each transaction is caculated from count of transactions made.So that the transaction id is sequential 
#####            You can purchase As Much as produts you want
####                  *I created a while loop for that
####                  * You have to enter the number of products you want to purchase before starting the purchase
####            Discount will be reduced from the amount of each product
####            After the purchase the 'Items Available' atribute will be reduced 
#           
##    '3' : TO display Ratings of the products
##    '4' : To display Material composition
##    '5': TO Rate the product
###          Raings of the product is calculated and updated in correspondence with the number of persons rating the item
            
          