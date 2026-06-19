# ShopSmart_E-commerce_Project
Two complementary implementations are included in this repository:

1. **Manual Workflow** – A step-by-step implementation covering data preprocessing, feature encoding, train-test splitting, Decision Tree training, and model evaluation.
2. **Pipeline Workflow** – A production-oriented implementation leveraging Scikit-Learn's `Pipeline` and `ColumnTransformer` to automate preprocessing and model training.

To improve model generalization and reduce overfitting, multiple pre-pruning configurations were explored by tuning key Decision Tree hyperparameters such as `max_depth` and `min_samples_leaf`. Through systematic experimentation, the best-performing manually tuned model achieved an **F1 Score of 0.672**, surpassing the assignment benchmark of **0.55**.

This project demonstrates both foundational machine learning practices and industry-standard workflow design, highlighting the impact of preprocessing, hyperparameter tuning, and model optimization on classification performance.

