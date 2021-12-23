If an error message is displayed when opening the IPYNB files, please follow instructions below to access the content :

For Library Collection Inventory analysis: 
copy the follwowing link (github file link): 

For Library Item Checkouts analysis: 
copy the follwowing link (github file link): 

and
paste to - Jupyter Extension: https://nbviewer.org/





Data pre-processing: 
Data processing was executed using Old Dominion Univerisity's Open Demand application, to launch a Jupyter server using Python on the wahab cluster. Both datasets were retrieved from Seattle Library Open Data Program, and saved on the cluster that allows multiple cores for data storage. 

Item Checkouts by Title dataset from The Seattle Public Library (Checkouts by Title) contains 38,470,908 records, 11 columns in data set – UsageClass, CheckoutType, MaterialType, CheckoutYear, CheckoutMonth, Checkouts, Title, Creator, Subjects, Publisher, PublicationYear. From this dataset, Creator, and Subjects were ommitted for further consideration. 

The Library Collection Inventory (Collection Inventory) dataset contains 67, 716, 791 records, 12 columns in data set – BibNum, Title, Author, ISBN, PublicationYear, Publisher, Subjects, ItemType, ItemCollection, FloatingItem, ItemLocation, ReportDate, ItemCount. From the dataset, BibNum, ISBN, ItemLocation, and FloatingItem were ommited for analysis. 

Similar data count evaluations were made for other columns including Publisher from Collection Inventory, and Checkout Year from Checkouts by Title dataset. Performing this evaluation on Checkouts by Title for Checkout Year data reveals something that catches attention is a significant drop in the year 2020 time frame. Figure 6, shows the tally of checkouts for 2020 at an all time low since data recording has begun at 1,721,376 compared to 2005, first available time frame from the dataset at 1,331,652. For this trend change, no need to look further than the COVID lockdown restriction pleased around the country in early 2020. Since the time of data recording, there is a steady increase in Checkout tally over the years. This could be attributed to increasing availability of Checkout inventory items that are available both physically in book, CD, & DVD formats, as well as digital items including ebooks, audiobooks, & other digital format Item Types presented in Library Collection Inventory dataset.

Meaningful relationships are drawn the Inventory, and Checkout datasets. Trend in increasing checkout, is support by increasing library collection inventory. Furthermore, Checkout data in the top most common material types, is support by the quantity of item type collection inventory. Checkout data is also consistent in popular items and time frame. For example, decreasing trend during COVID shutdown. Further expansion of the project will investigate trends on a smaller time frame. Implement more advanced models to evaluate relationships between inventory, and checkout trends
