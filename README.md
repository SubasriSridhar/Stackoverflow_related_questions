<h4> Problem Statement </h4>
<p>
When you search for a dataset with a query on the system/platform,you're shown a list of related dataset search queries. How would you build such a system/platform that also generates a list of related searches for each query? 
</p>

The objective is to build a model which list the similar or semantically similar list of queries for the search criteria. 

**Model**



**Constraints and Future improvement:**

The model is just a POC. The dataset is limited to Python and Java related posts. Also, I have used only 500k data points adjusting to the capacity of my machine. And for faster results, I have limited the use of top 500 tags. This model could be worth further investigation with large datasets for better clustering accuracy.

Also due to time constraints, the model is limited to word embedding techniques . However, the model will be perfect if trained with artificial neural network which has dense vector representations and trying out topic modelling.

 References:
 https://medium.com/analytics-vidhya/stackoverflow-based-semantic-search-engine-139e2b2e8860 
 
 https://medium.com/analytics-vidhya/building-a-simple-stack-overflow-search-engine-to-predict-posts-related-to-given-query-post-56b3e508520c
 
 https://towardsdatascience.com/improving-the-stack-overflow-search-algorithm-using-semantic-search-and-nlp-a23e20091d4c
 
 https://www.microsoft.com/en-us/research/uploads/prod/2019/03/nl4se18LinkSO.pdf
 
 https://www.macadamian.com/learn/a-practical-application-of-machine-learning-in-medicine/
 
 https://mc.ai/stackoverflow-based-semantic-search-engine/
