# TechnovitDatathon24

## Search Terms:
- "Model selection cheat sheet"
- "Neural network / Deep learning for neural networks" (?)

## Elaborate References:
- https://machinelearningmastery.com/start-here/

## Pseudocode:

classification vs regression?

from sklearn.model_selection import train_test_split

data.read_csv
data.head()
data.value_counts()
data.describe()

how to handle null values?

Standard scaler

what if categorical values?

X_train, X_test, y_train, y_test = train_test_split(X, y)

model.train()
model.score()
model.predict

cross validation
for i in range(10):
    model.train(i)
    print(model.score())

result.to_csv(index=None)

Feature Selection
- Variance
- Correlations (recursive)

Visualisation
- Correlation matrix?

Null Values