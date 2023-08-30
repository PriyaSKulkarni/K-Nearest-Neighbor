# K-Nearest-Neighbor
CSE-6363-001-MACHINE LEARNING: K Nearest Neighbor

We are tasked with predicting the material type of a mug based on height, diameter, weight, and hue (color) measurements. We approach this using the K-Nearest Neighbors (KNN) algorithm with two different similarity measures. Here's the breakdown:

a) Using Cartesian distance as the similarity measure, we predict material types for the Evaluation data. We calculate distances, select neighbors, and predict material types for K values of 1, 3, and 5, leveraging corresponding training data.

b) Our KNN algorithm is implemented to handle various training data and take input data points for predictions.

c) For evaluating KNN's performance, we employ leave-one-out validation. We repeatedly train on the remaining data, predict the label for the excluded point, and calculate the percentage of erroneous predictions. We apply this with K values of 1, 3, and 5 on the Question 2c dataset, determining the best K for optimal accuracy.

d) We modify the KNN algorithm to use Manhattan distance (L1) as the similarity measure and repeat the leave-one-out validation. We compare the accuracy of both similarity measures for each K value.

e) We rerun the prediction experiment from part c), this time excluding the fourth attribute (hue). We use KNN with Cartesian distance and assess the prediction performance. We compare this with the previous scenario to determine whether including hue improves predictions.

In summary, we predict mug material types using KNN with different similarity measures and evaluate its accuracy through leave-one-out validation. We analyze the impact of different attributes and similarity measures on the prediction results.
