#  Customer_segmentation_using_RFM_Analysis
Segmentaion of the customer done based on their Purchasing and spending patteren,and frquencices of Purchase 
![main Template](https://user-images.githubusercontent.com/109585845/222420596-2f278416-f71b-46fa-bc25-fd281209d18b.png)


## Authors

- [@chandrashekhar G T](https://www.github.com/chandugt35295)


## Usage/Examples
import pandas as pd
df =pd.read_csc(r'file.csv')
## Customer Segmentation
This project aims to cluster the customers visited the store for the period of one year and segmenting them on RFM Analysis followed by ML Model Approach. The following documentation provides an overview of the data collection and preprocessing, feature selection, model selection and training, and interpretation of results for this customer Segmentation.
## Data Collection and Preprocessing
The data used for this project was obtained from [https://archive-beta.ics.uci.edu/dataset/352/online+retail]. The following variables were collected for each individual:
-This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online -----  retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. 
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.	
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides. 

# Customer Segmentation RFM Approach
The dataset contains more than 500K values and we checked for country with highest purchase and found UK has most Purchases and stareted te segmenting and grouped customer behavior in 3 groups GOLD,SILVER and BRONZE
![segmentation1](https://user-images.githubusercontent.com/109585845/222420484-34965014-2bd5-4ffc-8f5c-b2301c4654a5.png)

# Conclusion 

On segmenataion of Customers into 3 groups found that customers are showing 3 types of behaviour
1.Customers with high purchase and High Frequency
2.Customers with low purchase and less Frequency
3.one Time visit customers/Dropout Customes 
among these Dropout customers are highest compared to other 2 category,so we need to focus on these customers to increase their frequency in purchases by giving them
Target customer Discount,By targetting Them by Advertisements.
