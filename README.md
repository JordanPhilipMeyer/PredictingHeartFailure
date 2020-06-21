# Predicting Heart Failure

Neural network application to identify patients at high-risk for heart events (I)¶

> "We analyzed a dataset containing the medical records of 299 heart failure patients collected at the Faisalabad Institute of Cardiology and at the Allied Hospital in Faisalabad (Punjab, Pakistan), during April–December 2015 [52, 66]. The patients consisted of 105 women and 194 men, and their ages range between 40 and 95 years old (Table 1). All 299 patients had left ventricular systolic dysfunction and had previous heart failures that put them in classes III or IV of New York Heart Association (NYHA) classification of the stages of heart failure [67]."

https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5

*Motive* Predict patients that died before their next follow-up. Machine learning tools can be immensely helpful to identify patients at high risk for life-threatening heart events.

Results This model applies a random forest classifer with a few significant variables. That output is fed into a neural network and run through a few dozen one-cycle iterations to achieve an accuracy of 98% on the hold-out dataset. between

Part I In this notebook, you'll see exploratory data analysis of the dataset. This will help identify the critical features to build a random forest classifier. We also prep the datasets to be fed into the neural network in this part. In the next notebook, you'll see development and inference of the neural network.
