# mobilecredit

This report is a predictive analytics attempted to predict credit behavior (default vs non-default) of 1,000 Thai individuals from the ```testing``` set given a dataset of 1,000 individuals to work with for ```training``` and ```validation``` set. It is an answer to the [ML Club Chula Tournament 2](https://drive.google.com/file/d/0B1vlbhoEpEY8Z2wxMW9jUUFDVkE/view) by [ML Club Chula](https://www.facebook.com/MLClubChula/). 

With respect to [Bjorkegen and Grissen (2015)](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2611775), we extracted features from call pattern, mobile payment pattern and demographics of the sample. Feature data was collected throughout 2014 and the response data was collected in the latter half of 2014.

We train random forest, svm with gaussian kernel and boosted logistic regression on the 60/40 training set, then validated resulting in random forest classifier having the largest AUC. We chose random forest to predict the testing set given.

Report is [here](http://cstorm125.github.io/mobilecredit).

GitHub repository is [here](https://github.com/cstorm125/mobilecredit).
