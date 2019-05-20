# KaggleHousePricePred

* Check for outliers and removed them
* normalized skewed output using box-cox transformation
* used sklearn varience threshold to remove columns having low varience
* used Chi square test to select best features which are having least RMS error on test data.
* used random forest regression with 1000 estimators to predict output.

