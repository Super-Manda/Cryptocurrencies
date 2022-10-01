# :coin: Cryptocurrencies :coin:

## :atom:  Purpose
###
There are important clients who are preparing to get into the cryptocurrency market.  One client, Accountability Accounting, a prominent investment bank, wishes to offer a new cryptocurrency investment portfolio to its customers, but is struggling to understand which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.  Since the expected output is unknown, unsupervised machine learning will be used.

## :atom:  Analysis
### In deliverable 1, the original dataset was cleaned and prepared.  
- This is the dataset after cleaning. Upon checking this DataFrame, the next step was to create variables for text features and scale it. 
![Deliverable1](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/deliverable1_crypto_df.png)


### In deliverable 2, Principal Component Analysis (PCA) was used to reduce data dimensions to 3 principal components.
- This is what the table looked like.

![Deliverable2](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/deliverable2_table.png)

### In deliverable 3, cryptocurrencies were clustered using k-means to group them.
- According to this Elbow Curve, there should be 4 clusters:
![Deliverable3a](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/deliverable3_elbow_curve.png)

- A 3d rotating graph was useful to see where the clusters existed.
![Deliverable3_3d](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/3d_graph.png) 


### In deliverable 4, the results were visualized and shared with this client.
- A table of tradable currencies was shown.
![Deliverable4_table](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/deliverable4_table_tradable_cryptos.png)

- A 2d scatterplt was also useful.
![Deliverable4_plot](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/deliverable4_2d_scatterplot.png) 


## :atom:  Conclusion

- In conclusion, all of these clusters tend to be dominated by currencies of low cost-- valued in the cents or less.  Although there are differences among the clusters, none of them stand out as clearly "the best cluster" unless we know what the client's particular need is.  
 
- Class 0 contains about half of the data points.  There are more recognizable names among them, such as Litecoin Cash and Cardano.
![class0](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/3d_graph_on_click_class0.png)


- Class 1 contains about half of the data points.  This appears to be a cast of unknown coins, some of them regional or used in particular games, such as NewYorkCoin and UFO.
![class1](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/3d_graph_on_click_class1.png)


- Class 2 is an outlier cluster that contains BitTorrent (BTT), which appears to be of near-zero value, but it does have name recognition due to its relationship with file-sharing. 
![class2](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/3d_graph_on_click_class2.png) 


- Class 3 is an outlier that contains Acute Angle (AAC), which also appears to be of very low value and a relatively unknown currency. 
![class3](https://github.com/Super-Manda/Cryptocurrencies/blob/main/images/3d_graph_on_click_class3.png)
