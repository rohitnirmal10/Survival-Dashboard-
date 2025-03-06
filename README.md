This App is an overlay package for libraries focused on model interpretability. It uses Shap or Lime backend to compute contributions. Shapash builds upon the various steps required to create a machine learning model, making the results more understandable.

This is suitable for Regression, Binary Classification or Multiclass problem.
It is compatible with numerous models: Catboost, Xgboost, LightGBM, Sklearn Ensemble, Linear models, SVM.

If your model is not in the list of compatible models, it is possible to provide this with local contributions calculated with shap or another method. Here's an example of how to provide contributions. An issue has been created to enhance this use case.

It can use category-encoders object, sklearn ColumnTransformer or simply features dictionary.

**Category_encoder**: OneHotEncoder, OrdinalEncoder, BaseNEncoder, BinaryEncoder, TargetEncoder

**Sklearn ColumnTransformer**: OneHotEncoder, OrdinalEncoder, StandardScaler, QuantileTransformer, PowerTransformer

**Examples:**

![Screenshot 2025-03-06 194645](https://github.com/user-attachments/assets/6dfb95ad-9d29-40f2-af8d-3dfb99a62a8f)
![saxax](https://github.com/user-attachments/assets/c5c93c2d-4434-47ee-a5fd-c7eb928fd40d)
