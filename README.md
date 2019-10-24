# DataScienceCapstone
Arvato's dataset on customer segmentation

**1) Libraries used**
To successfully run this Jupyter notebook the following libraries need be installed in the system   
 - Python 3   
 - Pandas   
 - Sklearn   
 - Seaborn   
 - Matplotlib   
 - Numpy   

**2) Motivation for the project**
The idea behind this project is to analyse what are the features that best identify potential customers for a given company. In order to do so, two datasets are provided, one that contains information of the whole population, and a second dataset with information about real customers. By studying these two datasets using unsupervised learning techniques it will be observed what are the particularities of customers when compare to the whole population. These findings, in turn, will enable better assess whether a new individual may be a potential customer. By using supervised machine learning algorithms, a recommendation on whether to target a new individual or not will be given. 

In short, the purpose of this study is twofold. First, to help a given company achieve a better understanding of what their current customers are, what is their profile and what are the features that set them apart.  Second, to help them be more efficient in their targeting campaign by using ML techniques that will assign certain probability to a new individual become a future customer.

**3) Files in the repository**   
*captoneWorkbook.ipynb* : This is the file that includes the whole detailed analysis with comments and snippets of code that were used to obtain final results.    

*myfile.txt*: This is the manually created file that help identify the invalid values for each of the features in the dataset.

*report.docx*: An more through descriptions of the steps taken and reasoning behind some of the decissions. It also contains main conclusions.   

**4) Summary of results**
Both report and notebook identify that the population of Germany can be clustered into 9 distinct groups, each with different characteristics. Out of these 9 clusters, it can be observed that there are three of them that are overrepresented in the customer dataset. This come to suggest that people that share the same characteritics as these groups are more likely to become customers for this company. A more detail description can be found in both report and notebook but in short the prototype customer is a middle-age individual with a confortable financial situation that is part of middle-class, upper-middle-class group. 

It has also been demonstrated that a classification algorithm can be designed to better predict new customers for this company. The notebook shows that a gradient boosting algorithm can be trained to predict with an AUC score of 0.7. This should not be taken as the maximum limit that a classification algorithm can aspire to, rather as a baseline to keep improving the model. This study is therefore by no means a final solution and it should motivate future readers and the author himself to keep improving this model by modifying both the wrangling process and the ML pipeline
