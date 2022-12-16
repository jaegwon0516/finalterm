# FinalTermProject
# Configuration instructions
## Brain Tumor MRI
- 뇌종양 데이터셋에는 4가지의 종류가 있습니다.
1) glioma tumor
2) meningioma tumor
3) pituitary tumor
4) no tumor
## VotingClassifier
- KNeighborsClassifier
- SVC
- SVC
- SVC
- DecisionTreeClassifier
- DecisionTreeClassifier
- DecisionTreeClassifier
## Hyper-parameter of the function
1) KNeighborsClassifier
- **n_neighbors :** Number of neighbors to use by default for kneighbors queries.
2) SVC
- **gamma :** Kernel coefficient for ‘rbf’, ‘poly’ and ‘sigmoid’.
- **random_state :** Controls the pseudo random number generation for shuffling the data for probability estimates. Ignored when probability is False. Pass an int for reproducible output across multiple function calls.
3) DecisionTreeClassifier
- **criterion :** The function to measure the quality of a split. Supported criteria are “gini” for the Gini impurity and “log_loss” and “entropy” both for the Shannon information gain.
- **random_state :** Controls the randomness of the estimator. The features are always randomly permuted at each split, even if splitter is set to "best".
- **max_features :** The number of features to consider when looking for the best split.
- **splitter :** The strategy used to choose the split at each node. Supported strategies are “best” to choose the best split and “random” to choose the best random split.
# Operating instructions
- 기기마다 정확도가 다르게 나와 pickle 파일로 모델을 저장했습니다.
- pickle 파일로 불러온 모델을 통해 정확도를 측정해주시기 바랍니다.
- 트레이닝 데이터를 늘리기 위해 0.3으로 split하던 것을 0.01로 변경했습니다.
# Copyright and licensing information
- MIT License
# Contact information
- 20223709 이재권
- jaegwon0516@cau.ac.kr
