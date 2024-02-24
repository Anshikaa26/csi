# Csi - Task 2 Machine Learning
## ABOUT ME
- **Name:** Anshika Misra
- **Registration Number:** 22BCT0081
## AIM
This task aims at addressing a situation involving a restaurant in suburban Bangalore where a significant number of people have reported food poisoning. As a government official in the food ministry, the task is to efficiently process a set of texts, to identify and group those related to the food poisoning incident. The ultimate goal is to generate a comprehensive project brief that can be submitted promptly to the superior.
## TASK INFORMATION
- **File Name:** Food_poisoning.ipynb 
- **Resource Used:** Google Colab
- **Dataset Name:** TextMsgs.csv (self-made)
- **Model used:** Kmeans Clustering
## TASK WORKFLOW
### 1. Data pre-processing
The data pre-processing section includes 3 subsections:
1. Importing the required libraries, here, pandas and matplotlib. 
2. Importing the dataset. The self-made dataset, TextMsgs.csv includes the texts received.
3. Cleaning the texts - removing the unwanted/repetitive texts, special characters and retaining the root of the word by using stemming.
### 2. Bag of words
This section aims at creating a bag of words model from the given dataset. A bag of words model converts the text representation to numerical representation based on the frequency of the occurence of a particular word.
### 3. Kmeans Clustering
This includes three sections:
1. The elbow method - which aims at finding the number of clusters
2. Kmeans clustering model is applied to the cleaned dataset. Here, the value of k=number of clusters is 3. This value will differ for different datasets. The  value can be obtained from the graph of the elbow method
3. Visualizing the clusters on a 2D graph by applying dimensionality reduction using principal component analysis (PCA)
### 4. Grouping similar texts
This section groups texts that have similar keywords. In other words, this section displays the clusters of similar texts and assigns a label to each cluster. 
### 5. Summary
This section provides information on the number of texts containing the word "food poisoning"
