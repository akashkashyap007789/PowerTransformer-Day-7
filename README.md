# Power Transformer on Concrete Strength Data

This project demonstrates the impact of PowerTransformer techniques (Box-Cox and Yeo-Johnson) on feature distributions and Linear Regression performance using the Concrete Compressive Strength dataset.

The goal is to show why checking data distribution and applying the right transformation is important before fitting linear models.

What’s done

Loaded and explored the concrete strength dataset

Split data into training and testing sets

Trained a baseline Linear Regression model on raw features

Evaluated performance using R² score and cross-validation

Analyzed feature distributions using histograms and Q–Q plots

Applied Box-Cox transformation (with lambda value analysis)

Applied Yeo-Johnson transformation for comparison

Re-trained Linear Regression on transformed features

Compared model performance before and after transformation

Key takeaway

Skewed numerical features negatively affect linear models.
Applying PowerTransformer helps normalize distributions and leads to more stable and improved regression performance without changing the model itself.
