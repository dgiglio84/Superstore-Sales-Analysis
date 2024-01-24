# Superstore Sales Analysis

**Goal**

To examine sales order data from a big-box store and develop conclusions based on various factors such as item profitability, geographical location, and customer loyalty.

**Analysis Process**

-	Imported dataset from Excel spreadsheet into Pandas using a Jupyter notebook. 
-	Manipulated data to obtain the desired findings.
-	Used Matplotlib to create visualizations as needed.
  
**About the Data**

This dataset was taken from Kaggle.com: https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales/data

It contains 9994 rows of sales transactions between 2011 and 2014.

**Annual Profit Analysis**

-	The store saw gradual growth with each year.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/fdddf457-a777-433b-bed5-8b7bbc2b1148)

-	Profits have steadily increased, but not at the same rate as sales.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/b2ee384b-aee3-4c22-84d1-316463b99a64)

**Geographical Analysis**

-	California and New York were the most profitable states, making over double of the revenues of every other state.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/4a300d1c-afb4-4f58-8f86-011927c693da)

-	10 states experienced a net loss. The state with the biggest loss was Texas with $25,729.44.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/58ee2bc4-e6b7-4996-8a77-5094492da54f)

**Profitability by Item**

-	The Canon imageCLASS 2200 Advanced Copier was the store’s most profitable item. With a profit of $25,199.94, it is more than triple the revenue of the 2nd most profitable item.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/9e1d9120-02a2-4584-9605-bdf775d9e3a8)

-	The Cubify CubeX 3D Printer Double Head Print was the least profitable item, with a net loss of $8,879.97.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/e02df8c4-a35d-4455-bb01-c13ba6134d6a)

-	A total 301 items (16%) resulted in a net loss.
  
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/737eee57-6bd7-4c66-9eb3-ae263306da53)
 

**Discount Analysis**

-	Out of the 9994 total transactions, 52% were discounted.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/b74bf827-3146-4dec-a371-76b969120db8)

**Shipping Analysis**

-	Shipping times saw a spike in 2012 but dropped significantly in the preceding years. 
-	The faster ship time seems to correlate with the annual profit.

![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/ebda42e9-fa83-454d-b46e-5d2298ff3e9d)

**Customer Gap Analysis** 
-	A total of 44 customers purchased items from 2011 to 2013, but not in 2014. 
-	Evaluating the customers who departed in 2014 can lead to more insight as to their exit. The screenshot below shows the customers in this list with the highest sales from 2011-2013.
  	
![image](https://github.com/dgiglio84/Superstore-Sales-Analysis/assets/120340086/ec6b1b7b-bdc2-4b04-8194-d6098ba87d6a)

For more information, please see the Jupyter notebook included in this repository.  