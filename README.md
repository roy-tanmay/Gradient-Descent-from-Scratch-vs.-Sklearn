# Gradient-Descent-from-Scratch-vs.-Sklearn

In this project, I implemented Linear Regression using Gradient Descent without relying on sklearn.
Then, I compared the results with sklearn’s LinearRegression.

### What I Did

- Implemented gradient descent step by step in Python.

- Compared it with sklearn’s regression line.

- Verified that both give very similar results.

### Technologies Used

- Python

- NumPy

- Matplotlib 

- Sklearn (for comparison)

### Visualizing Gradient Descent

One cool part of this project was plotting all the lines that gradient descent tried before reaching the best fit.
This shows how the algorithm iteratively improves:

- At first, the lines are random and far from the data.

- With each step, they get closer.

- Finally, they converge to the same line.

[Link:](https://github.com/roy-tanmay/Gradient-Descent-from-Scratch-vs.-Sklearn/blob/main/Gradient_plot.png)

### Results

- **Gradient descent:-** **Coef :** 1.0177381667350405, **Intercept :** 1.9150826165722297'\
  **sklearn:-** **Coef :** 1.01773624, **Intercept :** 1.9152193111568891

- In both cases coefficient and intercept are identical

### Key Takeaways

Sklearn makes regression easy, but building it from scratch helped me understand how the algorithm actually works.
Gradient Descent is powerful and generalizes to higher dimensions too.
