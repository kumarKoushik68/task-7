 KNN Classification on Iris Dataset
 Project Overview
This project implements the K-Nearest Neighbors (KNN) algorithm to classify species of iris flowers based on their physical features.  
It is part of AI & ML Internship - Task 6 and focuses on understanding instance-based learning, the importance of feature normalization, and how the value of `K` affects accuracy.


 Dataset
Dataset Used: [Iris Dataset]  
The dataset contains150 samples of iris flowers, with:
- 4 features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
- Target variable: `species` (Setosa, Versicolor, Virginica)



 Tools & Libraries
- Python 3
- Pandas– data manipulation
- NumPy – numerical operations
- Matplotlib / Seaborn – visualizations
- Scikit-learn – model building & evaluation

Steps Performed
1. Data Loading & Exploration
   - Loaded dataset from `iris.csv`
   - Checked for missing values and dataset summary

2. Data Preprocessing
   - Separated features (`X`) and target (`y`)
   - Normalized features using `StandardScaler` (important for distance-based algorithms like KNN)

3. Train-Test Split
   - Split dataset into 80% training and 20% testing sets

4. Model Building
   - Implemented `KNeighborsClassifier` from `scikit-learn`
   - Trained with `k=5` (later tested multiple K values)

5. Evaluation
   - Measured accuracy
   - Created confusion matrix & classification report
   - Visualized confusion matrix using heatmap

6. K Value Optimization
   - Tested `K` from 1 to 20
   - Plotted `K vs Accuracy` to find the optimal number of neighbors

