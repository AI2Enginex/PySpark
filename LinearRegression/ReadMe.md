# Linear Regression using PySpark

# PySpark DataFrame

PySpark DataFrame, a distributed collection of data organized into named columns, served as the backbone of my project. With its distributed computing capabilities, PySpark DataFrame seamlessly processed large-scale data across multiple nodes in a cluster, unlocking the potential of big data analytics.

Key characteristics of PySpark DataFrame include:

Distributed Computing: Enables parallel processing of data across a cluster of computers, ensuring scalability and high performance.

Immutable: Ensures data integrity and facilitates fault tolerance.

Schema Enforcement: Specifies data types and nullable properties of each column, ensuring data consistency and efficiency.

Lazy Evaluation: Optimizes performance by postponing computation until necessary.

SQL Interface: Provides a SQL-like interface for querying data, making it easy to leverage SQL skills for data analysis and manipulation.

Integration with MLlib: Seamlessly integrates with MLlib, PySpark's machine learning library, enabling scalable model building and training.

# EDA

Exploratory Data Analysis (EDA) is crucial for understanding our data before diving into model building. With PySpark, I was able to efficiently analyze key insights from our dataset.
 
# Key steps in my project included:

1] Data preprocessing: handling missing values, encoding categorical features, and feature scaling.

2] Feature engineering: creating new features and selecting relevant ones for model training.

3] Model training and evaluation: using PySpark's MLlib to build a Linear and RandomForest Regression model, and evaluating its performance using metrics like RMSE and R-squared.
