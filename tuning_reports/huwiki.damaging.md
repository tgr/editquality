# Model tuning report
- Revscoring version: 2.1.0
- Features: editquality.feature_lists.huwiki.damaging
- Date: 2018-02-19T23:26:42.779348
- Observations: 39674
- Labels: [true, false]
- Statistic: roc_auc.labels.true (maximize)
- Folds: 5

# Top scoring configurations
| model            |   roc_auc.labels.true | params                                                                 |
|:-----------------|----------------------:|:-----------------------------------------------------------------------|
| GradientBoosting |                0.935  | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=700 |
| GradientBoosting |                0.9341 | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=500 |
| GradientBoosting |                0.9338 | learning_rate=0.01, max_depth=3, max_features="log2", n_estimators=700 |
| GradientBoosting |                0.9335 | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=300  |
| GradientBoosting |                0.9335 | learning_rate=0.1, max_depth=5, max_features="log2", n_estimators=100  |
| GradientBoosting |                0.9331 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=500  |
| GradientBoosting |                0.933  | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=500 |
| GradientBoosting |                0.9327 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=700  |
| GradientBoosting |                0.9321 | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=300 |
| GradientBoosting |                0.932  | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=500  |

# Models
## BernoulliNB
|   roc_auc.labels.true | params   |
|----------------------:|:---------|
|                0.8433 |          |

## RandomForestClassifier
|   roc_auc.labels.true | params                                                                          |
|----------------------:|:--------------------------------------------------------------------------------|
|                0.9315 | criterion="entropy", max_features="log2", n_estimators=640, min_samples_leaf=13 |
|                0.9308 | criterion="entropy", max_features="log2", n_estimators=320, min_samples_leaf=7  |
|                0.9302 | criterion="gini", max_features="log2", n_estimators=320, min_samples_leaf=13    |
|                0.9299 | criterion="entropy", max_features="log2", n_estimators=320, min_samples_leaf=13 |
|                0.9296 | criterion="entropy", max_features="log2", n_estimators=160, min_samples_leaf=13 |
|                0.9295 | criterion="entropy", max_features="log2", n_estimators=640, min_samples_leaf=7  |
|                0.9293 | criterion="entropy", max_features="log2", n_estimators=320, min_samples_leaf=3  |
|                0.9292 | criterion="gini", max_features="log2", n_estimators=640, min_samples_leaf=13    |
|                0.929  | criterion="entropy", max_features="log2", n_estimators=640, min_samples_leaf=5  |
|                0.9286 | criterion="gini", max_features="log2", n_estimators=640, min_samples_leaf=7     |
|                0.9286 | criterion="gini", max_features="log2", n_estimators=320, min_samples_leaf=5     |
|                0.9281 | criterion="entropy", max_features="log2", n_estimators=320, min_samples_leaf=5  |
|                0.9279 | criterion="entropy", max_features="log2", n_estimators=640, min_samples_leaf=3  |
|                0.9278 | criterion="gini", max_features="log2", n_estimators=640, min_samples_leaf=5     |
|                0.9275 | criterion="entropy", max_features="log2", n_estimators=160, min_samples_leaf=7  |
|                0.9275 | criterion="entropy", max_features="log2", n_estimators=160, min_samples_leaf=3  |
|                0.9274 | criterion="gini", max_features="log2", n_estimators=80, min_samples_leaf=5      |
|                0.9273 | criterion="gini", max_features="log2", n_estimators=160, min_samples_leaf=7     |
|                0.9273 | criterion="entropy", max_features="log2", n_estimators=80, min_samples_leaf=13  |
|                0.927  | criterion="gini", max_features="log2", n_estimators=160, min_samples_leaf=13    |
|                0.9266 | criterion="entropy", max_features="log2", n_estimators=640, min_samples_leaf=1  |
|                0.9263 | criterion="gini", max_features="log2", n_estimators=320, min_samples_leaf=7     |
|                0.9261 | criterion="entropy", max_features="log2", n_estimators=40, min_samples_leaf=13  |
|                0.9255 | criterion="gini", max_features="log2", n_estimators=640, min_samples_leaf=3     |
|                0.9247 | criterion="entropy", max_features="log2", n_estimators=160, min_samples_leaf=5  |
|                0.9246 | criterion="gini", max_features="log2", n_estimators=640, min_samples_leaf=1     |
|                0.9244 | criterion="gini", max_features="log2", n_estimators=160, min_samples_leaf=5     |
|                0.9243 | criterion="entropy", max_features="log2", n_estimators=80, min_samples_leaf=7   |
|                0.924  | criterion="gini", max_features="log2", n_estimators=80, min_samples_leaf=7      |
|                0.9233 | criterion="entropy", max_features="log2", n_estimators=80, min_samples_leaf=5   |
|                0.9231 | criterion="gini", max_features="log2", n_estimators=320, min_samples_leaf=3     |
|                0.9229 | criterion="gini", max_features="log2", n_estimators=160, min_samples_leaf=3     |
|                0.9228 | criterion="gini", max_features="log2", n_estimators=40, min_samples_leaf=13     |
|                0.9228 | criterion="gini", max_features="log2", n_estimators=80, min_samples_leaf=13     |
|                0.9224 | criterion="entropy", max_features="log2", n_estimators=80, min_samples_leaf=3   |
|                0.9205 | criterion="entropy", max_features="log2", n_estimators=40, min_samples_leaf=7   |
|                0.9198 | criterion="entropy", max_features="log2", n_estimators=40, min_samples_leaf=5   |
|                0.9183 | criterion="entropy", max_features="log2", n_estimators=320, min_samples_leaf=1  |
|                0.9181 | criterion="gini", max_features="log2", n_estimators=40, min_samples_leaf=7      |
|                0.917  | criterion="gini", max_features="log2", n_estimators=320, min_samples_leaf=1     |
|                0.9149 | criterion="entropy", max_features="log2", n_estimators=160, min_samples_leaf=1  |
|                0.9143 | criterion="gini", max_features="log2", n_estimators=40, min_samples_leaf=5      |
|                0.914  | criterion="entropy", max_features="log2", n_estimators=20, min_samples_leaf=7   |
|                0.9135 | criterion="gini", max_features="log2", n_estimators=160, min_samples_leaf=1     |
|                0.9125 | criterion="gini", max_features="log2", n_estimators=20, min_samples_leaf=7      |
|                0.9111 | criterion="entropy", max_features="log2", n_estimators=20, min_samples_leaf=13  |
|                0.9092 | criterion="gini", max_features="log2", n_estimators=80, min_samples_leaf=3      |
|                0.9084 | criterion="gini", max_features="log2", n_estimators=20, min_samples_leaf=13     |
|                0.907  | criterion="gini", max_features="log2", n_estimators=20, min_samples_leaf=5      |
|                0.9069 | criterion="gini", max_features="log2", n_estimators=40, min_samples_leaf=3      |
|                0.9022 | criterion="entropy", max_features="log2", n_estimators=40, min_samples_leaf=3   |
|                0.9019 | criterion="entropy", max_features="log2", n_estimators=10, min_samples_leaf=13  |
|                0.9015 | criterion="entropy", max_features="log2", n_estimators=80, min_samples_leaf=1   |
|                0.8996 | criterion="gini", max_features="log2", n_estimators=20, min_samples_leaf=3      |
|                0.8988 | criterion="entropy", max_features="log2", n_estimators=20, min_samples_leaf=5   |
|                0.8958 | criterion="gini", max_features="log2", n_estimators=10, min_samples_leaf=13     |
|                0.8943 | criterion="gini", max_features="log2", n_estimators=10, min_samples_leaf=7      |
|                0.8935 | criterion="gini", max_features="log2", n_estimators=80, min_samples_leaf=1      |
|                0.8934 | criterion="entropy", max_features="log2", n_estimators=20, min_samples_leaf=3   |
|                0.8876 | criterion="entropy", max_features="log2", n_estimators=10, min_samples_leaf=7   |
|                0.8818 | criterion="gini", max_features="log2", n_estimators=10, min_samples_leaf=5      |
|                0.8792 | criterion="entropy", max_features="log2", n_estimators=10, min_samples_leaf=5   |
|                0.8783 | criterion="entropy", max_features="log2", n_estimators=40, min_samples_leaf=1   |
|                0.8698 | criterion="gini", max_features="log2", n_estimators=40, min_samples_leaf=1      |
|                0.8573 | criterion="entropy", max_features="log2", n_estimators=10, min_samples_leaf=3   |
|                0.8482 | criterion="gini", max_features="log2", n_estimators=10, min_samples_leaf=3      |
|                0.8261 | criterion="gini", max_features="log2", n_estimators=20, min_samples_leaf=1      |
|                0.8213 | criterion="entropy", max_features="log2", n_estimators=20, min_samples_leaf=1   |
|                0.785  | criterion="entropy", max_features="log2", n_estimators=10, min_samples_leaf=1   |
|                0.7827 | criterion="gini", max_features="log2", n_estimators=10, min_samples_leaf=1      |

## GaussianNB
| roc_auc.labels.true   | params   |
||

## LogisticRegression
|   roc_auc.labels.true | params              |
|----------------------:|:--------------------|
|                0.9197 | C=1, penalty="l1"   |
|                0.919  | C=10, penalty="l1"  |
|                0.9168 | C=0.1, penalty="l1" |
|                0.7768 | C=1, penalty="l2"   |
|                0.774  | C=0.1, penalty="l2" |
|                0.7635 | C=10, penalty="l2"  |

## GradientBoosting
|   roc_auc.labels.true | params                                                                 |
|----------------------:|:-----------------------------------------------------------------------|
|                0.935  | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=700 |
|                0.9341 | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=500 |
|                0.9338 | learning_rate=0.01, max_depth=3, max_features="log2", n_estimators=700 |
|                0.9335 | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=300  |
|                0.9335 | learning_rate=0.1, max_depth=5, max_features="log2", n_estimators=100  |
|                0.9331 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=500  |
|                0.933  | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=500 |
|                0.9327 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=700  |
|                0.9321 | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=300 |
|                0.932  | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=500  |
|                0.9317 | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=300 |
|                0.9316 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=300  |
|                0.9315 | learning_rate=0.01, max_depth=3, max_features="log2", n_estimators=500 |
|                0.9315 | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=700 |
|                0.9308 | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=100  |
|                0.9284 | learning_rate=0.5, max_depth=1, max_features="log2", n_estimators=300  |
|                0.9279 | learning_rate=0.5, max_depth=1, max_features="log2", n_estimators=100  |
|                0.9273 | learning_rate=0.1, max_depth=7, max_features="log2", n_estimators=100  |
|                0.927  | learning_rate=0.1, max_depth=5, max_features="log2", n_estimators=300  |
|                0.9268 | learning_rate=0.01, max_depth=3, max_features="log2", n_estimators=300 |
|                0.9253 | learning_rate=0.01, max_depth=7, max_features="log2", n_estimators=100 |
|                0.9253 | learning_rate=0.5, max_depth=1, max_features="log2", n_estimators=500  |
|                0.9242 | learning_rate=0.01, max_depth=5, max_features="log2", n_estimators=100 |
|                0.9233 | learning_rate=0.1, max_depth=3, max_features="log2", n_estimators=700  |
|                0.9199 | learning_rate=0.5, max_depth=1, max_features="log2", n_estimators=700  |
|                0.9193 | learning_rate=0.1, max_depth=1, max_features="log2", n_estimators=100  |
|                0.9186 | learning_rate=0.01, max_depth=1, max_features="log2", n_estimators=700 |
|                0.9155 | learning_rate=0.01, max_depth=1, max_features="log2", n_estimators=500 |
|                0.9151 | learning_rate=0.01, max_depth=3, max_features="log2", n_estimators=100 |
|                0.9148 | learning_rate=0.1, max_depth=5, max_features="log2", n_estimators=500  |
|                0.911  | learning_rate=0.01, max_depth=1, max_features="log2", n_estimators=300 |
|                0.904  | learning_rate=0.01, max_depth=1, max_features="log2", n_estimators=100 |
|                0.8997 | learning_rate=0.5, max_depth=3, max_features="log2", n_estimators=100  |
|                0.8994 | learning_rate=1, max_depth=1, max_features="log2", n_estimators=500    |
|                0.8991 | learning_rate=1, max_depth=1, max_features="log2", n_estimators=700    |
|                0.8986 | learning_rate=0.5, max_depth=3, max_features="log2", n_estimators=300  |
|                0.8965 | learning_rate=0.1, max_depth=7, max_features="log2", n_estimators=300  |
|                0.8959 | learning_rate=0.1, max_depth=5, max_features="log2", n_estimators=700  |
|                0.895  | learning_rate=1, max_depth=1, max_features="log2", n_estimators=300    |
|                0.8818 | learning_rate=0.5, max_depth=5, max_features="log2", n_estimators=100  |
|                0.8742 | learning_rate=0.5, max_depth=3, max_features="log2", n_estimators=500  |
|                0.853  | learning_rate=0.1, max_depth=7, max_features="log2", n_estimators=500  |
|                0.8486 | learning_rate=0.5, max_depth=3, max_features="log2", n_estimators=700  |
|                0.8241 | learning_rate=1, max_depth=3, max_features="log2", n_estimators=100    |
|                0.8088 | learning_rate=0.1, max_depth=7, max_features="log2", n_estimators=700  |
|                0.8034 | learning_rate=0.5, max_depth=7, max_features="log2", n_estimators=100  |
|                0.7966 | learning_rate=0.5, max_depth=5, max_features="log2", n_estimators=300  |
|                0.7928 | learning_rate=1, max_depth=3, max_features="log2", n_estimators=300    |
|                0.7801 | learning_rate=0.5, max_depth=7, max_features="log2", n_estimators=300  |
|                0.7778 | learning_rate=0.5, max_depth=7, max_features="log2", n_estimators=500  |
|                0.7756 | learning_rate=0.5, max_depth=7, max_features="log2", n_estimators=700  |
|                0.765  | learning_rate=1, max_depth=3, max_features="log2", n_estimators=700    |
|                0.7557 | learning_rate=1, max_depth=5, max_features="log2", n_estimators=100    |
|                0.7359 | learning_rate=0.5, max_depth=5, max_features="log2", n_estimators=700  |
|                0.7348 | learning_rate=0.5, max_depth=5, max_features="log2", n_estimators=500  |
|                0.7232 | learning_rate=1, max_depth=7, max_features="log2", n_estimators=100    |
|                0.7231 | learning_rate=1, max_depth=3, max_features="log2", n_estimators=500    |
|                0.6969 | learning_rate=1, max_depth=5, max_features="log2", n_estimators=300    |
|                0.6483 | learning_rate=1, max_depth=7, max_features="log2", n_estimators=300    |
|                0.6071 | learning_rate=1, max_depth=5, max_features="log2", n_estimators=700    |

