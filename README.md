This project explores public data Library Collection Inventory, and Item Checkouts data made available, and maintained by Seattle Public Library Open Data Program. Each data set is first analyzed for trends individually. Then, comparison, and relationships between the two datasets are investigated. This project intended to explore relationships between item inventory collection, and checkout records. Library item inventory is always changing in quantity, as well as in variaiation. Variation in this case referes to types of items. Library inventory changes from only printed items, to digital items such as  VHS, CDs, & DVDS, then to AudioBooks & eBooks so forth, and so on. Similarly, checkout records also follow similar trends in types of items being checked out, based on material availaility, and persons interests. This project explored trends in Inventory Collection since 1900s, and for Checkout Items beginning in 2015. Natrually, because of limited data availaility, more investigative analysis is performed for Library Inventory dataset. 

Individual exploration of Item Checkouts dataset focused on exploring change in type of items being checked out. And, explored amount of items being checked out, specific focus is made for pre, and post-COVID time period. During the same period in May 2019 timeframe, specific topics being checked out is explored. This time period is also time where social unrest was present in the US due to racial issues.

Individual exploration of library item collection inventory focused on change in inventory size of specific material types over time. A clear increase in digital item collection inventory is identified. Additionally, yearly publication data is explored in this dataset.

Dataset Details: 

1) Item Checkouts by Title (Checkouts): 
    Contains 38,470,908 records, 11 columns in data set – UsageClass, CheckoutType, MaterialType, CheckoutYear, CheckoutMonth, Checkouts, Title, Creator, Subjects, Publisher, PublicationYear. From this dataset, Creator, 
   
   and

2) The Library Collection Inventory (Collection Inventory): 
    Contains 67, 716, 791 records, 12 columns in data set – BibNum, Title, Author, ISBN, PublicationYear, Publisher, Subjects, ItemType,                   ItemCollection, FloatingItem, ItemLocation, ReportDate, ItemCount. From the     dataset, BibNum, ISBN, ItemLocation, and FloatingItem were ommited for         analysis. 

Dataset Source: 
Checkouts - https://data.seattle.gov/Community/Checkouts-By-Title-Physical-Items-/5src-czff

Collection Inventory - https://data.seattle.gov/Community/Library-Collection-Inventory/6vkj-f5xf


If an error message is displayed when opening the IPYNB files, please follow instructions below to access the content :

For Library Collection Inventory analysis: 
copy the follwowing link (github file link): https://github.com/kagst27/SeattlePublicLibraryData/blob/main/Library_Inventory_Data_Analysis_SI.ipynb

For Library Item Checkouts analysis: 
copy the follwowing link (github file link): https://github.com/kagst27/SeattlePublicLibraryData/blob/main/CheckoutsbyTitleFI.ipynb

and
paste to - Jupyter Extension: https://nbviewer.org/


Data pre-processing: 
Data processing was executed using Old Dominion Univerisity's Open Demand application, to launch a Jupyter server using Python on the wahab cluster. Both datasets were retrieved from Seattle Library Open Data Program, and saved on the cluster that allows multiple cores for data storage. 


Similar data count evaluations were made for other columns including Publisher from Collection Inventory, and Checkout Year from Checkouts by Title dataset. Performing this evaluation on Checkouts by Title for Checkout Year data reveals something that catches attention is a significant drop in the year 2020 time frame. Figure 6, shows the tally of checkouts for 2020 at an all time low since data recording has begun at 1,721,376 compared to 2005, first available time frame from the dataset at 1,331,652. For this trend change, no need to look further than the COVID lockdown restriction pleased around the country in early 2020. Since the time of data recording, there is a steady increase in Checkout tally over the years. This could be attributed to increasing availability of Checkout inventory items that are available both physically in book, CD, & DVD formats, as well as digital items including ebooks, audiobooks, & other digital format Item Types presented in Library Collection Inventory dataset.

Further expansion of the project will investigate trends on a smaller time frame. Implement more advanced models to evaluate relationships between inventory, and checkout trends
