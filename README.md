# iris-project
Answer to the programming question using iris

Existence of a significant statistical association between iris type and input features:

For the DummyClassifier, a p-value of 1.0 indicates that the observed classification accuracy or score is likely obtained by chance. This means there is no significant statistical association between the iris type and the input features when using a dummy classifier.
However, for the HistGradientBoostingClassifier, a p-value of 0.0099 (approximately 0.01) suggests that the observed classification accuracy or score is unlikely to be obtained by chance. Therefore, there is a significant statistical association between the iris type and the input features when using the gradient boosting classifier.
Ability of each estimator to assess the statistical association:

The DummyClassifier, which simply predicts the most frequent class, does not have the ability to capture the underlying patterns or associations in the data. Hence, it fails to assess the statistical association effectively, resulting in a high p-value (1.0).
In contrast, the HistGradientBoostingClassifier is a more sophisticated model that can learn complex relationships between the input features and the target variable. The low p-value (0.0099) suggests that it is capable of accurately capturing the statistical association between the iris type and the input features.
In summary, while the dummy classifier fails to detect any meaningful association, the HistGradientBoostingClassifier identifies a significant statistical association between the iris type and the input features, indicating its superior ability to capture the underlying patterns in the data.
