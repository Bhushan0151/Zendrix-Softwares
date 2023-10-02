from sklearn.pipeline import Pipeline
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression

# Define the steps in the pipeline
steps = [
    ('scaler', StandardScaler()),         # Step 1: Data preprocessing (scaling)
    ('classifier', LogisticRegression())  # Step 2: Machine learning model (Logistic Regression)
]

# Create the pipeline
pipeline = Pipeline(steps)

# Now you can fit the pipeline to your data and make predictions
# For example:
# pipeline.fit(X_train, y_train)
# y_pred = pipeline.predict(X_test)
