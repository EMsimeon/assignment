Create a function named calculate_discount(price, discount_percent) that calculates the final price after applying a discount. The function should take the original price (price) and the discount percentage (discount_percent) as parameters. If the discount is 20% or higher, apply the discount; otherwise, return the original price.
def calculate_discount(price,discount_percent):
calculate the final price after applying a discount if the discount is 20% or higher
parameters:
price (float):original price 
discount_percent(float):Discount
Percentage(0-100)
Returns:
float :Final price after discount
(or original price if discount <=20%)
if discount_percent>=20:
    returns price *(100-disccount_percent)/100-
    ele:
    return price

Using the calculate_discount function, prompt the user to enter the original price of an item and the discount percentage. Print the final price after applying the discount, or if no discount was applied, print the original price.
def calculate_discount (price discount_percent):
calculate the final price after applying a discount if the discount is 20% or higher.
  Parameters :
  price (float ):Original price 
  discount_percent (float ) :Discount 
  percentage (0-100)
  Returns:
  float :Final price after discount
  (or original price if  discount <20%)
  if discount _percent >=20
      return price *(100-discount-percent)/100
      else:
      return price
      #Get user input
      original_price =float (input ("Enter the original price of the item :ksh :))
      discount _percent =float (input ("Enter the discount percentage :"))
      #Calculate final price 
       final_price =
       calculate _discount (original_price,discount_percent)
       #Display results
       if discount _percent>=20
            print(f"Final price after (discount_percent)%discount:ksh(final_price :.2f)")
            else:
                print(f no discount applied.Original price :ksh(original _price:.2f)")
      
