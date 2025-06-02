# Day-5

Decision Tree and Random Forest

The steps followed are as follows:-
1. Did not standardize the data this time since decision tree and random forest do not need it.
2. split the data and used the validation data to find the depth which gives the best accuracy. Checked for overfitting by plotting the graph between training accuracies and validation accuracies. But both kept increasing and flattened out so there is no overfitting till depth 10.
3. Used the best model to predict on Test data and achieved 97.56% accuracy.
4. Similarly, Random Forest achieved an accuracy of 99.0% as expected since it generalises better and so achieves higher accuracy than decision tree.
5. Plotted feature importance next and finally checked the cross-validation score.
