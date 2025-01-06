## Gradient Descent and Data Visualization

### Project Overview

This project is divided into two main parts:

1. **Classification with Gradient Descent**: Implementation of gradient descent algorithms for multiple linear and logistic regression. The project includes derivations, testing on simulated data and a comparison with other classification algorithms.
2. **Data Visualization**: Creation of an interactive map using Folium, showcasing Baltimore crime data with graphical elements for better understanding.

### Objectives

### Part 1: Classification with Gradient Descent
1. Implement gradient descent for multiple linear and logistic regression.
2. Derive and explain the gradient update equation for logistic regression.
3. Simulate datasets for testing implementations and validate parameter recovery.
4. Compare logistic regression performance with two other algorithms using 10-fold cross-validation and paired t-tests.

#### Part 2: Data Visualization
1. Visualize Baltimore crime data on an interactive map using Folium.
2. Add graphical elements to enhance understanding (used color-coded markers by sex and race).
3. Embed the interactive map in the notebook for presentation.

### Methodology

#### Part 1: Classification
1. **Gradient Descent Implementation**:
   - Developed batch and stochastic gradient descent algorithms for regression tasks.
   - Commented and documented the code for clarity.

2. **Simulated Data Testing**:
   - Linear regression: Used make_regression from sklearn to generate data.
   - Logistic regression: Converted continuous outputs into binary classes.

3. **Algorithm Comparison**:
   - Compared logistic regression against two selected algorithms:
     - Random Forest
     - Support Vector Machines (SVM)
   - Evaluated performance using 10-fold cross-validation and paired t-tests.

#### Part 2: Interactive Data Map
1. Used Folium to create a map of Baltimore crimes.
2. Added markers with attributes like sex and race for visual insights.
3. Embedded the map in the notebook for user interaction.

### Tools and Libraries Used

- **Gradient Descent**: numpy, pandas, matplotlib, sklearn
- **Statistical Testing**: scipy.stats
- **Visualization**: matplotlib, folium
- **Dataset**: Baltimore crime data (BPD_Arrests.csv)


