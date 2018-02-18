# Model tuning report
- Revscoring version: 2.1.0
- Features: editquality.feature_lists.huwiki.reverted
- Date: 2018-02-17T08:00:15.362979
- Observations: 39674
- Labels: [true, false]
- Statistic: roc_auc.labels.true (maximize)
- Folds: 5

# Top scoring configurations
| model                  |   roc_auc.labels.true | params                                                                          |
|:-----------------------|----------------------:|:--------------------------------------------------------------------------------|
| RandomForestClassifier |                0.9232 | min_samples_leaf=3, criterion="entropy", n_estimators=320, max_features="log2"  |
| RandomForestClassifier |                0.9228 | min_samples_leaf=5, criterion="entropy", n_estimators=160, max_features="log2"  |
| RandomForestClassifier |                0.9226 | min_samples_leaf=5, criterion="entropy", n_estimators=320, max_features="log2"  |
| RandomForestClassifier |                0.9223 | min_samples_leaf=5, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier |                0.922  | min_samples_leaf=1, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier |                0.9217 | min_samples_leaf=7, criterion="entropy", n_estimators=640, max_features="log2"  |
| RandomForestClassifier |                0.9216 | min_samples_leaf=13, criterion="entropy", n_estimators=640, max_features="log2" |
| RandomForestClassifier |                0.9212 | min_samples_leaf=13, criterion="entropy", n_estimators=160, max_features="log2" |
| RandomForestClassifier |                0.9211 | min_samples_leaf=7, criterion="entropy", n_estimators=320, max_features="log2"  |
| RandomForestClassifier |                0.9207 | min_samples_leaf=13, criterion="entropy", n_estimators=320, max_features="log2" |

# Models
## GradientBoosting
|   roc_auc.labels.true | params                                                                 |
|----------------------:|:-----------------------------------------------------------------------|
|                0.917  | learning_rate=0.01, n_estimators=700, max_features="log2", max_depth=7 |
|                0.917  | learning_rate=0.01, n_estimators=700, max_features="log2", max_depth=5 |
|                0.9162 | learning_rate=0.01, n_estimators=500, max_features="log2", max_depth=7 |
|                0.9158 | learning_rate=0.1, n_estimators=100, max_features="log2", max_depth=5  |
|                0.9149 | learning_rate=0.1, n_estimators=300, max_features="log2", max_depth=3  |
|                0.9144 | learning_rate=0.01, n_estimators=500, max_features="log2", max_depth=5 |
|                0.9136 | learning_rate=0.01, n_estimators=300, max_features="log2", max_depth=7 |
|                0.9123 | learning_rate=0.1, n_estimators=100, max_features="log2", max_depth=3  |
|                0.9119 | learning_rate=0.1, n_estimators=500, max_features="log2", max_depth=3  |
|                0.9114 | learning_rate=0.01, n_estimators=700, max_features="log2", max_depth=3 |
|                0.9108 | learning_rate=0.1, n_estimators=300, max_features="log2", max_depth=5  |
|                0.9106 | learning_rate=0.01, n_estimators=300, max_features="log2", max_depth=5 |
|                0.9088 | learning_rate=0.1, n_estimators=700, max_features="log2", max_depth=3  |
|                0.908  | learning_rate=0.1, n_estimators=100, max_features="log2", max_depth=7  |
|                0.908  | learning_rate=0.01, n_estimators=100, max_features="log2", max_depth=7 |
|                0.9056 | learning_rate=0.01, n_estimators=500, max_features="log2", max_depth=3 |
|                0.9044 | learning_rate=0.1, n_estimators=700, max_features="log2", max_depth=1  |
|                0.9028 | learning_rate=0.1, n_estimators=500, max_features="log2", max_depth=5  |
|                0.9028 | learning_rate=0.01, n_estimators=100, max_features="log2", max_depth=5 |
|                0.9019 | learning_rate=0.5, n_estimators=300, max_features="log2", max_depth=1  |
|                0.901  | learning_rate=0.1, n_estimators=500, max_features="log2", max_depth=1  |
|                0.9005 | learning_rate=0.1, n_estimators=700, max_features="log2", max_depth=5  |
|                0.9005 | learning_rate=0.5, n_estimators=500, max_features="log2", max_depth=1  |
|                0.8987 | learning_rate=0.5, n_estimators=700, max_features="log2", max_depth=1  |
|                0.897  | learning_rate=0.01, n_estimators=300, max_features="log2", max_depth=3 |
|                0.8968 | learning_rate=0.5, n_estimators=100, max_features="log2", max_depth=1  |
|                0.8966 | learning_rate=0.1, n_estimators=300, max_features="log2", max_depth=1  |
|                0.8959 | learning_rate=0.1, n_estimators=300, max_features="log2", max_depth=7  |
|                0.8957 | learning_rate=0.5, n_estimators=100, max_features="log2", max_depth=3  |
|                0.892  | learning_rate=1, n_estimators=100, max_features="log2", max_depth=1    |
|                0.8889 | learning_rate=1, n_estimators=500, max_features="log2", max_depth=1    |
|                0.8869 | learning_rate=0.01, n_estimators=100, max_features="log2", max_depth=3 |
|                0.8861 | learning_rate=0.5, n_estimators=100, max_features="log2", max_depth=5  |
|                0.8839 | learning_rate=1, n_estimators=300, max_features="log2", max_depth=1    |
|                0.883  | learning_rate=0.1, n_estimators=100, max_features="log2", max_depth=1  |
|                0.8814 | learning_rate=1, n_estimators=700, max_features="log2", max_depth=1    |
|                0.8814 | learning_rate=0.01, n_estimators=700, max_features="log2", max_depth=1 |
|                0.8797 | learning_rate=0.5, n_estimators=300, max_features="log2", max_depth=3  |
|                0.8791 | learning_rate=0.01, n_estimators=500, max_features="log2", max_depth=1 |
|                0.8766 | learning_rate=0.01, n_estimators=300, max_features="log2", max_depth=1 |
|                0.8763 | learning_rate=0.5, n_estimators=500, max_features="log2", max_depth=3  |
|                0.8715 | learning_rate=0.01, n_estimators=100, max_features="log2", max_depth=1 |
|                0.8687 | learning_rate=0.5, n_estimators=700, max_features="log2", max_depth=3  |
|                0.8606 | learning_rate=0.1, n_estimators=500, max_features="log2", max_depth=7  |
|                0.8545 | learning_rate=1, n_estimators=100, max_features="log2", max_depth=3    |
|                0.8441 | learning_rate=0.5, n_estimators=100, max_features="log2", max_depth=7  |
|                0.8364 | learning_rate=1, n_estimators=300, max_features="log2", max_depth=3    |
|                0.8344 | learning_rate=0.1, n_estimators=700, max_features="log2", max_depth=7  |
|                0.833  | learning_rate=1, n_estimators=500, max_features="log2", max_depth=3    |
|                0.8279 | learning_rate=0.5, n_estimators=300, max_features="log2", max_depth=5  |
|                0.8119 | learning_rate=0.5, n_estimators=700, max_features="log2", max_depth=7  |
|                0.8114 | learning_rate=0.5, n_estimators=700, max_features="log2", max_depth=5  |
|                0.8077 | learning_rate=1, n_estimators=100, max_features="log2", max_depth=5    |
|                0.8067 | learning_rate=0.5, n_estimators=500, max_features="log2", max_depth=7  |
|                0.7998 | learning_rate=0.5, n_estimators=500, max_features="log2", max_depth=5  |
|                0.7997 | learning_rate=0.5, n_estimators=300, max_features="log2", max_depth=7  |
|                0.7691 | learning_rate=1, n_estimators=500, max_features="log2", max_depth=5    |
|                0.7689 | learning_rate=1, n_estimators=700, max_features="log2", max_depth=3    |
|                0.7651 | learning_rate=1, n_estimators=700, max_features="log2", max_depth=5    |
|                0.7578 | learning_rate=1, n_estimators=300, max_features="log2", max_depth=5    |
|                0.7446 | learning_rate=1, n_estimators=100, max_features="log2", max_depth=7    |
|                0.7184 | learning_rate=1, n_estimators=500, max_features="log2", max_depth=7    |
|                0.6665 | learning_rate=1, n_estimators=300, max_features="log2", max_depth=7    |

## LogisticRegression
|   roc_auc.labels.true | params              |
|----------------------:|:--------------------|
|                0.8884 | penalty="l1", C=10  |
|                0.888  | penalty="l1", C=0.1 |
|                0.8876 | penalty="l1", C=1   |
|                0.6589 | penalty="l2", C=1   |
|                0.6514 | penalty="l2", C=0.1 |
|                0.6452 | penalty="l2", C=10  |

## RandomForestClassifier
|   roc_auc.labels.true | params                                                                          |
|----------------------:|:--------------------------------------------------------------------------------|
|                0.9232 | min_samples_leaf=3, criterion="entropy", n_estimators=320, max_features="log2"  |
|                0.9228 | min_samples_leaf=5, criterion="entropy", n_estimators=160, max_features="log2"  |
|                0.9226 | min_samples_leaf=5, criterion="entropy", n_estimators=320, max_features="log2"  |
|                0.9223 | min_samples_leaf=5, criterion="entropy", n_estimators=640, max_features="log2"  |
|                0.922  | min_samples_leaf=1, criterion="entropy", n_estimators=640, max_features="log2"  |
|                0.9217 | min_samples_leaf=7, criterion="entropy", n_estimators=640, max_features="log2"  |
|                0.9216 | min_samples_leaf=13, criterion="entropy", n_estimators=640, max_features="log2" |
|                0.9212 | min_samples_leaf=13, criterion="entropy", n_estimators=160, max_features="log2" |
|                0.9211 | min_samples_leaf=7, criterion="entropy", n_estimators=320, max_features="log2"  |
|                0.9207 | min_samples_leaf=13, criterion="entropy", n_estimators=320, max_features="log2" |
|                0.9201 | min_samples_leaf=3, criterion="entropy", n_estimators=640, max_features="log2"  |
|                0.9193 | min_samples_leaf=7, criterion="gini", n_estimators=320, max_features="log2"     |
|                0.9186 | min_samples_leaf=3, criterion="entropy", n_estimators=160, max_features="log2"  |
|                0.9185 | min_samples_leaf=7, criterion="gini", n_estimators=640, max_features="log2"     |
|                0.918  | min_samples_leaf=5, criterion="gini", n_estimators=640, max_features="log2"     |
|                0.9179 | min_samples_leaf=3, criterion="gini", n_estimators=640, max_features="log2"     |
|                0.9179 | min_samples_leaf=13, criterion="gini", n_estimators=640, max_features="log2"    |
|                0.9179 | min_samples_leaf=5, criterion="gini", n_estimators=320, max_features="log2"     |
|                0.917  | min_samples_leaf=13, criterion="gini", n_estimators=320, max_features="log2"    |
|                0.9168 | min_samples_leaf=5, criterion="gini", n_estimators=160, max_features="log2"     |
|                0.9166 | min_samples_leaf=7, criterion="entropy", n_estimators=160, max_features="log2"  |
|                0.9162 | min_samples_leaf=1, criterion="gini", n_estimators=640, max_features="log2"     |
|                0.9159 | min_samples_leaf=13, criterion="gini", n_estimators=160, max_features="log2"    |
|                0.9158 | min_samples_leaf=3, criterion="gini", n_estimators=320, max_features="log2"     |
|                0.9155 | min_samples_leaf=5, criterion="entropy", n_estimators=80, max_features="log2"   |
|                0.9153 | min_samples_leaf=13, criterion="entropy", n_estimators=80, max_features="log2"  |
|                0.915  | min_samples_leaf=7, criterion="gini", n_estimators=160, max_features="log2"     |
|                0.914  | min_samples_leaf=1, criterion="entropy", n_estimators=320, max_features="log2"  |
|                0.9134 | min_samples_leaf=3, criterion="gini", n_estimators=160, max_features="log2"     |
|                0.9132 | min_samples_leaf=13, criterion="gini", n_estimators=80, max_features="log2"     |
|                0.9129 | min_samples_leaf=7, criterion="gini", n_estimators=80, max_features="log2"      |
|                0.9124 | min_samples_leaf=5, criterion="entropy", n_estimators=40, max_features="log2"   |
|                0.9124 | min_samples_leaf=3, criterion="entropy", n_estimators=80, max_features="log2"   |
|                0.9119 | min_samples_leaf=7, criterion="entropy", n_estimators=40, max_features="log2"   |
|                0.9116 | min_samples_leaf=1, criterion="gini", n_estimators=320, max_features="log2"     |
|                0.9116 | min_samples_leaf=7, criterion="entropy", n_estimators=80, max_features="log2"   |
|                0.9113 | min_samples_leaf=7, criterion="gini", n_estimators=40, max_features="log2"      |
|                0.911  | min_samples_leaf=13, criterion="entropy", n_estimators=40, max_features="log2"  |
|                0.9103 | min_samples_leaf=13, criterion="gini", n_estimators=40, max_features="log2"     |
|                0.9097 | min_samples_leaf=3, criterion="gini", n_estimators=80, max_features="log2"      |
|                0.9085 | min_samples_leaf=5, criterion="gini", n_estimators=80, max_features="log2"      |
|                0.9083 | min_samples_leaf=13, criterion="entropy", n_estimators=20, max_features="log2"  |
|                0.9052 | min_samples_leaf=5, criterion="gini", n_estimators=40, max_features="log2"      |
|                0.904  | min_samples_leaf=1, criterion="entropy", n_estimators=160, max_features="log2"  |
|                0.9039 | min_samples_leaf=1, criterion="gini", n_estimators=160, max_features="log2"     |
|                0.8993 | min_samples_leaf=5, criterion="entropy", n_estimators=20, max_features="log2"   |
|                0.8988 | min_samples_leaf=13, criterion="gini", n_estimators=20, max_features="log2"     |
|                0.8986 | min_samples_leaf=3, criterion="entropy", n_estimators=40, max_features="log2"   |
|                0.8984 | min_samples_leaf=1, criterion="entropy", n_estimators=80, max_features="log2"   |
|                0.8975 | min_samples_leaf=5, criterion="gini", n_estimators=20, max_features="log2"      |
|                0.8954 | min_samples_leaf=7, criterion="gini", n_estimators=20, max_features="log2"      |
|                0.8939 | min_samples_leaf=1, criterion="gini", n_estimators=80, max_features="log2"      |
|                0.893  | min_samples_leaf=7, criterion="gini", n_estimators=10, max_features="log2"      |
|                0.893  | min_samples_leaf=13, criterion="entropy", n_estimators=10, max_features="log2"  |
|                0.8924 | min_samples_leaf=7, criterion="entropy", n_estimators=20, max_features="log2"   |
|                0.892  | min_samples_leaf=7, criterion="entropy", n_estimators=10, max_features="log2"   |
|                0.8919 | min_samples_leaf=3, criterion="gini", n_estimators=40, max_features="log2"      |
|                0.8882 | min_samples_leaf=13, criterion="gini", n_estimators=10, max_features="log2"     |
|                0.8863 | min_samples_leaf=3, criterion="entropy", n_estimators=20, max_features="log2"   |
|                0.8831 | min_samples_leaf=3, criterion="gini", n_estimators=20, max_features="log2"      |
|                0.879  | min_samples_leaf=5, criterion="gini", n_estimators=10, max_features="log2"      |
|                0.8785 | min_samples_leaf=1, criterion="gini", n_estimators=40, max_features="log2"      |
|                0.8731 | min_samples_leaf=1, criterion="entropy", n_estimators=40, max_features="log2"   |
|                0.8718 | min_samples_leaf=5, criterion="entropy", n_estimators=10, max_features="log2"   |
|                0.8601 | min_samples_leaf=3, criterion="gini", n_estimators=10, max_features="log2"      |
|                0.853  | min_samples_leaf=3, criterion="entropy", n_estimators=10, max_features="log2"   |
|                0.8521 | min_samples_leaf=1, criterion="entropy", n_estimators=20, max_features="log2"   |
|                0.8434 | min_samples_leaf=1, criterion="gini", n_estimators=20, max_features="log2"      |
|                0.8091 | min_samples_leaf=1, criterion="gini", n_estimators=10, max_features="log2"      |
|                0.8009 | min_samples_leaf=1, criterion="entropy", n_estimators=10, max_features="log2"   |

## GaussianNB
| roc_auc.labels.true   | params   |
||

## BernoulliNB
|   roc_auc.labels.true | params   |
|----------------------:|:---------|
|                0.8113 |          |

