                
                        Part - 1
                Answer To Question 1

AIOps refers to the real time operations, i.e. how it supports and reacts to the issues in real times and then report the analytics of the same. AIOps combines big data and machine learning to automate IT processes. Since there is a lot of data available today to the big firms, it is quite hard to manage, collect, clean and then make the best analyzation of that data. So AIOps helps DevOps and DataOps to automate from development to production,find anomalies and much more. So, in short, it uses ML techniques intelligently to diagnose the issues, and then report to the technical teams in a much easier way to understand so that they can work on the same and the end goal  is to automatically spot issues in day-to-day IT operations and proactively react to them using AI.

MLOps, on the other hand, focuses on creating an automated pipeline for bringing machine learning models into production. It looks to overcome the disconnect between data science or data ops teams and infrastructure teams, to get models into production faster and more often.
MLOps or AIOps both aim to serve the same end goal; i.e. business automation. While MLOps bridges the gap between model building and deployment, AIOps focuses on determining and reacting to issues in IT operations in real-time so as to manage risks independently.

Sources Used-
1) https://betterprogramming.pub/mlops-vs-aiops-6e5354704dab
2) https://opensource.com/article/21/2/aiops-vs-mlops
3) https://www.rackspace.com/en-in/solve/aiops-and-mlops-not-same-thing
4) https://www.unraveldata.com/resources/dataops-aiops-and-mlops/



                Answer to Question 2


Basically, Linear Regression model predicts the target as a weighted sum of the feature inputs, i.e. it assumes the following form - 
        y =β0+β1x1+…+βpxp+ϵ
where The betas (βj) represent the learned feature weights or coefficients. The first weight in the sum (β0) is called the intercept and is not multiplied with a feature. The epsilon (ϵ) is the error we still make, i.e. the difference between the prediction and the actual outcome

Now the interpretation of weights in LR can be done in many ways-
1) If features are numerical, increasing the numerical feature by one unit changes the estimated outcome by its weight.
2) If features are binary, i.e. each outcome can be encoded as 0 or 1, then a change in a particular feature from one category to another simply changes the estimation by the weight of that feature.
3) If features are multiclass categorical type, we use one hot encoding format to represent those features, and the interpretation is same as binary.

There's a popular way of interpreting how well our LR performs where features are categorical, namely the R^2 method, which is calculated as follows- 

            R^2 = 1−(SSE/SST)
SSE == Squared sum of error terms and SST is the squared sum of the data variance.
Interpretation of constant term(β0): Not that relevant because features and their weights mainly contribute to the outcome, but can be a determining factor when features and weights are normalized.

Other way of interpretating LR features can be Visual Interpretations, where we represent the correlations between each feature and the overall outcome using boxplots. 

So such ways of encoding, evaluation and plots helps making the Linear regression interpretable and we can thus carry out the feature extraction effectively for representing the data in minimum dimensions(or features).

Source - https://christophm.github.io/interpretable-ml-book/limo.html


                 Answer to Question 3


AutoML Essentially Involves The Automation Of The Edge Process Of Obtaining Machine Learning To Real-World Problems That Are Actually Relevant To The Sector. Since It Is A Time-Consuming Task To Apply Traditional Machine Learning Methods To Real-World Solutions, AutoML essentially comes into the picture.

It is related to MLOps because MLOps is applying the ML models to the deployment phase, where we use it to solve real world problems, whereas AutoML is the automated version of MLOps, where we have pre defined tools which automatically apply those ML models.

Tools used in AutoML:

1) AutoKeras - Open-source software library for automated machine learning (AutoML). It is developed by DATA Lab at Texas A&M University and community contributors.
Functionality -  Provides functions to automatically search for architecture and hyperparameters of deep learning models.

2) H2OAutoML - Automatic machine learning module provided  by H2O, an open source distributed in-memory machine learning platform with linear scalability.
Functionality - Used for automating the machine learning workflow,  which includes automatic training and tuning of many models within a user-specified time-limit.

3) AUTO SKLEARN - Built around the scikit-learn machine learning library, Auto-sklearn provides out-of-the-box supervised machine learning. 
Functionality - Automatically searches for the right learning algorithm for a new machine learning dataset and optimizes its hyperparameters. 

4) AUTO-PYTORCH - Built around the Pytorch machine learning library.
Functionality - Automates  right architecture and hyperparameter settings by using multi-fidelity optimization and Bayesian optimization (BOHB) to search for the best settings.

5) AUTO-FOLIO - Algorithm selection (AS) techniques — which involve choosing from a set of algorithms the one expected to solve a given problem instance most efficiently — have substantially improved the state-of-the-art in solving many prominent AI problems.
Functionality- AutoFolio uses algorithm configuration to optimize the performance of algorithm selection systems by determining the best selection approach and its hyperparameters.

Sources Used-
1) https://pianalytix.com/why-do-we-have-automl-and-mlops/
2) https://searchsoftwarequality.techtarget.com/feature/Analysts-mixed-on-future-growth-of-MLOps-AutoML-tools
3) https://analyticsindiamag.com/10-popular-automl-tools-developers-can-use/

                Part 2
        
![Getting Started](AWS_Console.jpg)