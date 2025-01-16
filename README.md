# Excel-Dashboard--Women-Apparels-Sales-Report

IN THIS EXCEL SHEETS -:

1. Understanding the  Columns in the dataset

(i)index -: serial number
(ii) OrderId -: contains the ordered number
(iii)CustID -: contains the customer id
(iv)Gender -: Women/W/Men/M
(v)Age -: age of the customer
(vi)Date -: Date when the product .....
(vii)Status -: Cancelled /Delivered/Refunded /Returned
(viii)Channel -> Myntra/Meesho/Flipkart the PLATFORM
(ix)SKU -:....
(x)Category -: wheather the product is blouse/bottom/ethnicdress/kurta/saree/set/top/westendress
(xi)Size -: size of that product /category
(xii)Qty -: one/two/1/2/3/4
(xiii)Currency-: INR
(xv)Amount -: the price of the product
(xvi)ship-city -: city which the product have been shipped
(xvii)ship-state -: state which the product have been shipped
(xviii)ship-postal-state -: postal code to which the product have been shipped
(xix)ship-country -: Country which the product have been shipped(IN)
(xx)B2B -:....


2. Objective
          
Create an annual sales report for year 2022.
So that, Lakshmi Store can understand their customers
and grow more sales by getting the insights of the
data. 


3. Understanding and Analysing the data

(I)Compare Sales and orders using the single chart
(II)which Month Got the highest Sales and Orders
(III)Who purchase more Men Or Women         
(IV)What are different order status 
(V)Top 5 states contributing to the sales
(VI)Relation Between Age and Gender on the number of sales
(VII)Which channel in comntributing to the maximum number of orders
(VIII)Highest selling category?
(IX)Which product was purchased more


4. DATA CLEANING 

a. we will go through the entire column and look what we need to
    change/ update in the data

b. We always apply FILTER

c. Gender-> not consistent -> M/Men/W/Women
     we will make Men / Women   CTRL+F

d. Qty -> one -1 and two-2

and check all the columns and avoid if there are null in 
important columns like customer id , product id, Amount


5. DATA PROCESSING

Any process in data or manipulating that may help you in 
representing your data

a.  On the basis of age we make a category
   
if age=>50 'Senior' 
age>=30 'Adult'
else Teenage 

b. We extract the 2 column month and year for ease in further 
   calculation

7. DATA ANALYSIS-:

a. our first thing is sum of orders and count of item based on 
   months

we will use pivot table
values ->amount,order_id
representation-> chart
(We get to know that max sale was on the month of MARCH
and orders was on month or MARCH maximum)


b. Gender wise we go to pivot table and select gender with
   order_id(count) and respect to that a pie chart is created 

c. Status -> now here we again pivot table-> status and order_id
             (count) and get an area chart

d. Top 5 states
   Pivot table -> select state and then select the sum of
   amount and then filter(right click and sort)

e. Age and gender wise->
   select age group(the same col we created for different age 
   groups)
   axis-> age_group legend-> Gender values->amount
          (here amount in percent form)->  right click -> show value of % of grand tot

f. WE CREATE another chart of channels -> to see where the orders
   were maximum(through which platform)

      pivot table -> SELECT order id count
                     and channels


g. we create a pie graph -> for CATEGORY and sum of AMOUNT




h. SLICERS  -> take of MONTH ,CHANNEL and CATEGORY make   
        connections with every pivot table(every slicers)



INSIGHTS--->

1.Women buy more products as compared to Male
   Women(Adult b/w 30-50) are more likely to buy products.
2. Maharashtra , Karnataka ,UP are top state to buy product

3. Amazon contributes more through the channel.

4.The Category which is purchased more is SET


Final  ->.Women(Adult b/w 30-50) in Maharashtra, Karnataka ,UP 
             who purschses through Amazon,Flipkart and Myntra must
             be provided with exiting offers and Coupons to boost more sales.
             Should include more men products (new and trendy) to 
             increase the sale through male customer.
             Sets stocks must be more and must include different
             variety for more options to customer.
