# K-Nearest-Neighbors
KNN is a supervised learning algorithm used for classification and regression tasks. It works by finding the K nearest data points (neighbors) to a given test sample and then predicts the output based on the majority class (for classification) or average value (for regression) of those neighbors.  

🔹 How it Works
(1) Choose the number of neighbors (K).
(2) Calculate the distance between the new data point and all training samples (commonly Euclidean distance).
(3) Pick the K nearest points.
(4) For classification → take majority voting.
(5) For regression → take average of values.
(6) The result is the predicted class/value.

If K = 3 and the 3 nearest neighbors of a test point belong to classes [A, A, B],
then the model predicts the test point belongs to Class A.

🔹 Advantages

✅ Simple and easy to implement
✅ No training phase required
✅ Works well with small datasets

🔹 Disadvantages

❌ Slow with large datasets
❌ Sensitive to noise and irrelevant features
❌ Requires feature scaling (like normalization)
