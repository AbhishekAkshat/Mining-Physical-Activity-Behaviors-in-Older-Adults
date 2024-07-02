# Mining Physical Activity Behaviors in Older Adults

This project focuses on mining physical activity behaviours by identifying and exploring physical activities (PA) between different individuals. We aim to test and develop unsupervised methods to recognise different physical activity behaviours among older adults. 

For this research project, we are using the data provided by the Growing Old Together Study, which consists of 164 participants whose daily activities were monitored using wearable sensors over the span of two weeks, one before and one after a lifestyle intervention. We aggregated the obtained data at various scales, i.e. we combined different window lengths and aggregation methods to obtain the best possible combination for our goals. After some initial analysis and pre-processing of the provided data, we selected 114 participants for our experiments. 

For every participant, we constructed frequency features per 30-second aggregation window. Afterwards, we extracted the features over all the hours and the days. 

Then, using the constructed feature dataset, we applied two unsupervised methods, namely the k-means clustering algorithm and the hierarchical clustering algorithm, to identify differences in activity behaviours for the concluded clusters. Based on these, we expect to identify active or less active behaviours among the participants. We also consider ways to optimise the feature dataset by reducing the dimensions of our data for our clustering tasks, such as principal component analysis. 

This research would help us to stimulate vital and healthy ageing among older people along with inspiration and motivation to get started and stay active for a longer, healthier and happier life.

_______________________________________________________________________________________
