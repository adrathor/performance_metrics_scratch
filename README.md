In this project I am going to create some performance metrics from scratch without thhe use of sklearn library. below are the metrics that I have created:

1. Confusion Matrix 

2. F1 Score 

3. AUC Score, you need to compute different thresholds and for each threshold compute tpr,fpr and then use numpy.trapz(tpr_array, fpr_array) https://stackoverflow.com/q/53603376/4084039, https://stackoverflow.com/a/39678975/4084039 Note: it should be numpy.trapz(tpr_array, fpr_array) not numpy.trapz(fpr_array, tpr_array)

4. Accuracy Score

This assignment is a part of Applied AI Course individual student tasks.
