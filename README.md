# Adult Income Prediction Project

- Checked the data, looked at distributions and missing values
- Cleaned the data and fixed missing data
- Made some new features to make the data easier for the model to understand:
  - Age groups 
  - Education groups
  - Marital status groups
  - Work hours categories
- Turned categorical data into numbers with one-hot and ordinal encoding
- Used different models like logistic regression, rfc, kn neighbors but i just ran just the lineer regression because to use other models for this dataset i needed to optimize them with different methods like random grid search or sampling the data but since it's not for work i passed them.
- Checked which paramaters works best with cross validation and made everything in a pipeline

---

## Results
- Best model: **Linear Regression(The only one I ran)** (accuracy: 0.8332746196063681)

