Data pre-processing: 
Data processing was executed using Old Dominion Univerisity's Open Demand application, to launch a Jupyter server using Python on the wahab cluster. Both datasets were retrieved from Seattle Library Open Data Program, and saved on the cluster that allows multiple cores for data storage. 

Item Checkouts by Title dataset from The Seattle Public Library (Checkouts by Title) contains 38,470,908 records, 11 columns in data set – UsageClass, CheckoutType, MaterialType, CheckoutYear, CheckoutMonth, Checkouts, Title, Creator, Subjects, Publisher, PublicationYear. From this dataset, Creator, and Subjects were ommitted for further consideration. 


The library inventory data has approximately 14.2% of Author data missing. I removed entries with missing Author data as it is not reasonable to attempt to determine that value based on other neighboring entries as if it is with numerical data. 

Accdrom	Media	CD-ROM	Adult/YoungAdult
Armfm			
Acvhs			
Armus			
Acdvd			
Arcd			
Jrbk			
Armap			
Pkbknh			
Arec			
Arpam			
Arper			
Acmap			
Bcbk			
Acmus			
Jccd			
Armfc			
Accd	Media	CD	Adult/YoungAdult
Arbk	Book	Book	Reference Adult/YoungAdult
Jcbk	Book 	Book 	Juv
Acbk	Book	Book	Adult/YoungAdult
			


The Library Collection Inventory (Collection Inventory) dataset contains 67, 716, 791 records, 12 columns in data set – BibNum, Title, Author, ISBN, PublicationYear, Publisher, Subjects, ItemType, ItemCollection, FloatingItem, ItemLocation, ReportDate, ItemCount. From the dataset, BibNum, ISBN, ItemLocation, and FloatingItem were ommited for analysis. 



Visualization 
I used a combination of historgram, and box plot charts to analyze trends overtime. The inventory data shows changing trends in Author, Publishers, and Item Type quantity available. 


Inventory change in Item Types, from a total of 20 as defined by XX

Increasing in 
Checkout Items during 2013, and 2020 show significant spikes showing a sudden trend change. Two periods were analyzed for trends. First, during 2013 period a sudden increase in checkouts of Harry Potter 
