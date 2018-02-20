# Model tuning report
- Revscoring version: 2.1.0
- Features: editquality.feature_lists.huwiki.goodfaith
- Date: 2018-02-19T23:41:47.386396
- Observations: 39674
- Labels: [true, false]
- Statistic: roc_auc.labels.true (maximize)
- Folds: 5

# Top scoring configurations
| model                  |   roc_auc.labels.true | params                                                                        |
|:-----------------------|----------------------:|:------------------------------------------------------------------------------|
| GradientBoosting       |                0.9841 | learning_rate=0.1, n_estimators=700, max_depth=7, max_features="log2"         |
| GradientBoosting       |                0.9832 | learning_rate=0.5, n_estimators=700, max_depth=7, max_features="log2"         |
| GradientBoosting       |                0.9825 | learning_rate=0.5, n_estimators=700, max_depth=5, max_features="log2"         |
| GradientBoosting       |                0.9824 | learning_rate=0.5, n_estimators=300, max_depth=7, max_features="log2"         |
| GradientBoosting       |                0.9819 | learning_rate=0.5, n_estimators=300, max_depth=5, max_features="log2"         |
| GradientBoosting       |                0.9818 | learning_rate=0.1, n_estimators=500, max_depth=7, max_features="log2"         |
| GradientBoosting       |                0.9727 | learning_rate=0.5, n_estimators=100, max_depth=7, max_features="log2"         |
| RandomForestClassifier |                0.9713 | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=1    |
| RandomForestClassifier |                0.9712 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=1 |
| GradientBoosting       |                0.9657 | learning_rate=0.5, n_estimators=700, max_depth=3, max_features="log2"         |

# Models
## RandomForestClassifier
|   roc_auc.labels.true | params                                                                          |
|----------------------:|:--------------------------------------------------------------------------------|
|                0.9713 | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=1      |
|                0.9712 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=1   |
|                0.9633 | max_features="log2", n_estimators=20, criterion="entropy", min_samples_leaf=1   |
|                0.9628 | max_features="log2", n_estimators=20, criterion="gini", min_samples_leaf=1      |
|                0.9539 | max_features="log2", n_estimators=40, criterion="gini", min_samples_leaf=1      |
|                0.9536 | max_features="log2", n_estimators=40, criterion="entropy", min_samples_leaf=1   |
|                0.953  | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=3      |
|                0.9518 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=3   |
|                0.9473 | max_features="log2", n_estimators=80, criterion="gini", min_samples_leaf=1      |
|                0.9467 | max_features="log2", n_estimators=20, criterion="entropy", min_samples_leaf=3   |
|                0.9466 | max_features="log2", n_estimators=80, criterion="entropy", min_samples_leaf=1   |
|                0.9431 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=5   |
|                0.9423 | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=5      |
|                0.9421 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=7   |
|                0.9384 | max_features="log2", n_estimators=160, criterion="gini", min_samples_leaf=1     |
|                0.9373 | max_features="log2", n_estimators=160, criterion="entropy", min_samples_leaf=1  |
|                0.9371 | max_features="log2", n_estimators=20, criterion="gini", min_samples_leaf=3      |
|                0.9368 | max_features="log2", n_estimators=20, criterion="entropy", min_samples_leaf=5   |
|                0.9347 | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=13     |
|                0.9341 | max_features="log2", n_estimators=40, criterion="entropy", min_samples_leaf=3   |
|                0.9322 | max_features="log2", n_estimators=20, criterion="entropy", min_samples_leaf=7   |
|                0.9316 | max_features="log2", n_estimators=20, criterion="gini", min_samples_leaf=5      |
|                0.9309 | max_features="log2", n_estimators=320, criterion="entropy", min_samples_leaf=1  |
|                0.9306 | max_features="log2", n_estimators=10, criterion="entropy", min_samples_leaf=13  |
|                0.9304 | max_features="log2", n_estimators=40, criterion="gini", min_samples_leaf=3      |
|                0.9304 | max_features="log2", n_estimators=10, criterion="gini", min_samples_leaf=7      |
|                0.93   | max_features="log2", n_estimators=20, criterion="gini", min_samples_leaf=7      |
|                0.9296 | max_features="log2", n_estimators=40, criterion="entropy", min_samples_leaf=5   |
|                0.929  | max_features="log2", n_estimators=80, criterion="entropy", min_samples_leaf=3   |
|                0.9282 | max_features="log2", n_estimators=160, criterion="entropy", min_samples_leaf=3  |
|                0.9281 | max_features="log2", n_estimators=320, criterion="entropy", min_samples_leaf=3  |
|                0.9278 | max_features="log2", n_estimators=320, criterion="gini", min_samples_leaf=1     |
|                0.9277 | max_features="log2", n_estimators=320, criterion="entropy", min_samples_leaf=5  |
|                0.9268 | max_features="log2", n_estimators=640, criterion="gini", min_samples_leaf=1     |
|                0.9264 | max_features="log2", n_estimators=640, criterion="entropy", min_samples_leaf=1  |
|                0.9262 | max_features="log2", n_estimators=80, criterion="gini", min_samples_leaf=3      |
|                0.9252 | max_features="log2", n_estimators=40, criterion="entropy", min_samples_leaf=7   |
|                0.9245 | max_features="log2", n_estimators=160, criterion="gini", min_samples_leaf=5     |
|                0.924  | max_features="log2", n_estimators=640, criterion="entropy", min_samples_leaf=7  |
|                0.9239 | max_features="log2", n_estimators=160, criterion="entropy", min_samples_leaf=13 |
|                0.9239 | max_features="log2", n_estimators=320, criterion="entropy", min_samples_leaf=7  |
|                0.9236 | max_features="log2", n_estimators=640, criterion="entropy", min_samples_leaf=13 |
|                0.9236 | max_features="log2", n_estimators=320, criterion="gini", min_samples_leaf=13    |
|                0.9228 | max_features="log2", n_estimators=160, criterion="entropy", min_samples_leaf=5  |
|                0.9227 | max_features="log2", n_estimators=40, criterion="gini", min_samples_leaf=7      |
|                0.9218 | max_features="log2", n_estimators=20, criterion="entropy", min_samples_leaf=13  |
|                0.9214 | max_features="log2", n_estimators=640, criterion="entropy", min_samples_leaf=5  |
|                0.9214 | max_features="log2", n_estimators=40, criterion="gini", min_samples_leaf=13     |
|                0.9213 | max_features="log2", n_estimators=640, criterion="gini", min_samples_leaf=7     |
|                0.9212 | max_features="log2", n_estimators=80, criterion="entropy", min_samples_leaf=7   |
|                0.921  | max_features="log2", n_estimators=320, criterion="entropy", min_samples_leaf=13 |
|                0.9209 | max_features="log2", n_estimators=640, criterion="gini", min_samples_leaf=13    |
|                0.9206 | max_features="log2", n_estimators=320, criterion="gini", min_samples_leaf=3     |
|                0.9204 | max_features="log2", n_estimators=80, criterion="gini", min_samples_leaf=13     |
|                0.9197 | max_features="log2", n_estimators=320, criterion="gini", min_samples_leaf=7     |
|                0.9195 | max_features="log2", n_estimators=20, criterion="gini", min_samples_leaf=13     |
|                0.9191 | max_features="log2", n_estimators=80, criterion="entropy", min_samples_leaf=5   |
|                0.9188 | max_features="log2", n_estimators=160, criterion="gini", min_samples_leaf=3     |
|                0.9187 | max_features="log2", n_estimators=640, criterion="gini", min_samples_leaf=5     |
|                0.9184 | max_features="log2", n_estimators=40, criterion="gini", min_samples_leaf=5      |
|                0.9183 | max_features="log2", n_estimators=160, criterion="gini", min_samples_leaf=7     |
|                0.9183 | max_features="log2", n_estimators=160, criterion="gini", min_samples_leaf=13    |
|                0.918  | max_features="log2", n_estimators=640, criterion="entropy", min_samples_leaf=3  |
|                0.918  | max_features="log2", n_estimators=80, criterion="entropy", min_samples_leaf=13  |
|                0.9172 | max_features="log2", n_estimators=80, criterion="gini", min_samples_leaf=5      |
|                0.9169 | max_features="log2", n_estimators=160, criterion="entropy", min_samples_leaf=7  |
|                0.9167 | max_features="log2", n_estimators=320, criterion="gini", min_samples_leaf=5     |
|                0.9166 | max_features="log2", n_estimators=80, criterion="gini", min_samples_leaf=7      |
|                0.9164 | max_features="log2", n_estimators=640, criterion="gini", min_samples_leaf=3     |
|                0.9163 | max_features="log2", n_estimators=40, criterion="entropy", min_samples_leaf=13  |

## GradientBoosting
|   roc_auc.labels.true | params                                                                 |
|----------------------:|:-----------------------------------------------------------------------|
|                0.9841 | learning_rate=0.1, n_estimators=700, max_depth=7, max_features="log2"  |
|                0.9832 | learning_rate=0.5, n_estimators=700, max_depth=7, max_features="log2"  |
|                0.9825 | learning_rate=0.5, n_estimators=700, max_depth=5, max_features="log2"  |
|                0.9824 | learning_rate=0.5, n_estimators=300, max_depth=7, max_features="log2"  |
|                0.9819 | learning_rate=0.5, n_estimators=300, max_depth=5, max_features="log2"  |
|                0.9818 | learning_rate=0.1, n_estimators=500, max_depth=7, max_features="log2"  |
|                0.9727 | learning_rate=0.5, n_estimators=100, max_depth=7, max_features="log2"  |
|                0.9657 | learning_rate=0.5, n_estimators=700, max_depth=3, max_features="log2"  |
|                0.965  | learning_rate=0.1, n_estimators=300, max_depth=7, max_features="log2"  |
|                0.9647 | learning_rate=0.5, n_estimators=500, max_depth=5, max_features="log2"  |
|                0.9579 | learning_rate=0.1, n_estimators=700, max_depth=5, max_features="log2"  |
|                0.9485 | learning_rate=0.5, n_estimators=500, max_depth=3, max_features="log2"  |
|                0.9455 | learning_rate=1, n_estimators=100, max_depth=7, max_features="log2"    |
|                0.9379 | learning_rate=0.5, n_estimators=100, max_depth=5, max_features="log2"  |
|                0.9375 | learning_rate=1, n_estimators=100, max_depth=5, max_features="log2"    |
|                0.9366 | learning_rate=0.1, n_estimators=500, max_depth=5, max_features="log2"  |
|                0.9327 | learning_rate=0.1, n_estimators=700, max_depth=1, max_features="log2"  |
|                0.9323 | learning_rate=0.1, n_estimators=500, max_depth=1, max_features="log2"  |
|                0.9287 | learning_rate=0.1, n_estimators=300, max_depth=1, max_features="log2"  |
|                0.9286 | learning_rate=0.01, n_estimators=700, max_depth=5, max_features="log2" |
|                0.9275 | learning_rate=0.1, n_estimators=100, max_depth=3, max_features="log2"  |
|                0.9267 | learning_rate=0.01, n_estimators=700, max_depth=3, max_features="log2" |
|                0.9264 | learning_rate=0.5, n_estimators=300, max_depth=1, max_features="log2"  |
|                0.9263 | learning_rate=0.01, n_estimators=500, max_depth=5, max_features="log2" |
|                0.9246 | learning_rate=0.01, n_estimators=300, max_depth=5, max_features="log2" |
|                0.9245 | learning_rate=0.01, n_estimators=500, max_depth=3, max_features="log2" |
|                0.9238 | learning_rate=0.5, n_estimators=300, max_depth=3, max_features="log2"  |
|                0.9227 | learning_rate=0.01, n_estimators=500, max_depth=7, max_features="log2" |
|                0.9226 | learning_rate=0.01, n_estimators=300, max_depth=7, max_features="log2" |
|                0.9222 | learning_rate=0.01, n_estimators=300, max_depth=3, max_features="log2" |
|                0.9215 | learning_rate=0.01, n_estimators=100, max_depth=7, max_features="log2" |
|                0.9213 | learning_rate=0.1, n_estimators=100, max_depth=5, max_features="log2"  |
|                0.9212 | learning_rate=0.1, n_estimators=300, max_depth=3, max_features="log2"  |
|                0.9208 | learning_rate=0.01, n_estimators=700, max_depth=7, max_features="log2" |
|                0.9201 | learning_rate=0.5, n_estimators=100, max_depth=1, max_features="log2"  |
|                0.9195 | learning_rate=0.5, n_estimators=500, max_depth=1, max_features="log2"  |
|                0.9189 | learning_rate=0.1, n_estimators=500, max_depth=3, max_features="log2"  |
|                0.9188 | learning_rate=0.5, n_estimators=700, max_depth=1, max_features="log2"  |
|                0.9187 | learning_rate=0.1, n_estimators=100, max_depth=1, max_features="log2"  |
|                0.9178 | learning_rate=0.01, n_estimators=100, max_depth=5, max_features="log2" |
|                0.917  | learning_rate=0.1, n_estimators=300, max_depth=5, max_features="log2"  |
|                0.9163 | learning_rate=0.01, n_estimators=700, max_depth=1, max_features="log2" |
|                0.9126 | learning_rate=0.01, n_estimators=500, max_depth=1, max_features="log2" |
|                0.9122 | learning_rate=0.01, n_estimators=300, max_depth=1, max_features="log2" |
|                0.9117 | learning_rate=0.1, n_estimators=700, max_depth=3, max_features="log2"  |
|                0.9114 | learning_rate=0.01, n_estimators=100, max_depth=3, max_features="log2" |
|                0.9093 | learning_rate=0.1, n_estimators=100, max_depth=7, max_features="log2"  |
|                0.9053 | learning_rate=0.01, n_estimators=100, max_depth=1, max_features="log2" |
|                0.9027 | learning_rate=1, n_estimators=300, max_depth=5, max_features="log2"    |
|                0.8959 | learning_rate=0.5, n_estimators=500, max_depth=7, max_features="log2"  |
|                0.8875 | learning_rate=0.5, n_estimators=100, max_depth=3, max_features="log2"  |
|                0.882  | learning_rate=1, n_estimators=700, max_depth=5, max_features="log2"    |
|                0.8725 | learning_rate=1, n_estimators=300, max_depth=7, max_features="log2"    |
|                0.8553 | learning_rate=1, n_estimators=700, max_depth=3, max_features="log2"    |
|                0.8191 | learning_rate=1, n_estimators=500, max_depth=3, max_features="log2"    |
|                0.8098 | learning_rate=1, n_estimators=500, max_depth=5, max_features="log2"    |
|                0.8085 | learning_rate=1, n_estimators=300, max_depth=3, max_features="log2"    |
|                0.8003 | learning_rate=1, n_estimators=100, max_depth=3, max_features="log2"    |
|                0.798  | learning_rate=1, n_estimators=700, max_depth=1, max_features="log2"    |
|                0.7863 | learning_rate=1, n_estimators=100, max_depth=1, max_features="log2"    |
|                0.7633 | learning_rate=1, n_estimators=700, max_depth=7, max_features="log2"    |
|                0.7497 | learning_rate=1, n_estimators=500, max_depth=1, max_features="log2"    |
|                0.7493 | learning_rate=1, n_estimators=300, max_depth=1, max_features="log2"    |
|                0.74   | learning_rate=1, n_estimators=500, max_depth=7, max_features="log2"    |

## GaussianNB
| roc_auc.labels.true   | params   |
||

## LogisticRegression
|   roc_auc.labels.true | params              |
|----------------------:|:--------------------|
|                0.9346 | penalty="l1", C=10  |
|                0.9337 | penalty="l1", C=1   |
|                0.9249 | penalty="l1", C=0.1 |
|                0.7789 | penalty="l2", C=1   |
|                0.7337 | penalty="l2", C=0.1 |
|                0.7294 | penalty="l2", C=10  |

## BernoulliNB
|   roc_auc.labels.true | params   |
|----------------------:|:---------|
|                0.8737 |          |

