Which flower species seems to be the most separable?
-Iris setosa is the most separable species.
-It forms its own distinct cluster in almost every feature pair, especially petal length and petal width.
-Versicolor and virginica partly overlap with each other.



Were you able to improve after GridSearch?
-No, there was no improvement.
-Both the default SVC() and the GridSearch model reached 98% accuracy on the 45 test samples.
-Both produced the same confusion matrix, with only one misclassified sample (a versicolor predicted as virginica).
-The default model was already very strong because the Iris dataset is small and the classes are well separated, so tuning C and gamma had little room to help.