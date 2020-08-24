<h4> Problem Statement </h4>
<p>
When you search for a dataset with a query on the system/platform,you're shown a list of related dataset search queries. How would you build such a system/platform that also generates a list of related searches for each query? 
</p>

The objective is to build a model which list the similar or semantically similar list of queries for the search criteria. 

**Constraints and Future improvement:**

The model is just a POC. The dataset is limited to Python and Java related posts. Also, I have used only 500k data points adjusting to the capacity of my machine. And for faster results, I have limited the use of top 500 tags. This model could be worth further investigation with large datasets for better clustering accuracy.

Also due to time constraints, the model is limited to word embedding techniques . However, the model will be perfect if trained with artificial neural network which has dense vector representations and trying out topic modelling.

 