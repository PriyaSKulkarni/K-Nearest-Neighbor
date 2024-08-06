# K-Nearest-Neighbor   
CSE-6363-001-MACHINE LEARNING under Manfred Huber: K Nearest Neighbor    

    
**Maximum Likelihood Estimation (MLE) and Maximum A Posteriori (MAP) Derivation:**  
1. We explore learning the parameter q in the geometric distribution representing boot failures. For MLE, we derive the optimization result using observed failure counts. For MAP, we use the Beta distribution as a conjugate prior for q. We show steps and results for both methods using the given dataset.

**K Nearest Neighbor (KNN) Material Prediction:**   
2. Now we address mug material prediction using KNN and various distance measures. Specifically:
a) Utilizing Cartesian distance, we predict material types for Evaluation data using generated training data for K values of 1, 3, and 5. We detail each step: distance calculation, neighbor selection, and final prediction.
b) We develop a flexible KNN algorithm that adapts to different training datasets and allows input for predictions.
c) Implementing leave-one-out evaluation, we assess the KNN algorithm's accuracy. We repeatedly train on reduced data and test on the excluded point to estimate erroneous predictions. We apply this to the Question 2c dataset for K values 1, 3, and 5, determining the best-performing K.
d) We enhance the KNN algorithm to use Manhattan distance (L1) and re-run the leave-one-out evaluation. We analyze which similarity measure performs better for different K values.
e) In another experiment, we repeat the prediction evaluation from part c) using KNN with Cartesian distance, while excluding the fourth attribute. We compare results to assess which data configuration yields superior predictions.

In summary, we address MLE and MAP derivation for boot failures, and we extensively explore KNN for mug material prediction, considering different distance metrics and scenarios.
