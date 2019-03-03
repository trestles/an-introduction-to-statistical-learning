
#### 1. Introduction

#### 2. Statistical Learning 15
- 2.1. What is Statistical Learning? 15
  - 2.1.1. Why estimate f? p17
  - 2.1.2. How do we estimate f? p21
  - 2.1.3. The Trade-off between prediction accuracy and Model Interpretability p24
  - 2.1.4. Supervised Versus Unsupervised Learning p26
  - 2.1.5. Regression Versus Classification Problems p28
- 2.2. Assessing Model Accuracy p29
  - 2.2.1. Measuring the Quality of fit 29
  - 2.2.2. The Bias-Variance Trade-Off p33
  - 2.2.3. The Classification Setting p37
- 2.3. Lab: Introduction to R p42
  - 2.3.1. Basic Commands p42
  - 2.3.2. Graphics p45
  - 2.3.3. Indexing Data p47
  - 2.3.4. Loading Data p48
  - 2.3.5. Additional Graphical and Numerical Summaries p49
- 2.4. Exercises p52

#### 3. Linear Regression p59
- 3.1. Simple Linear Regression p61
  - 3.1.1. Estimating the coefficients p61
  - 3.1.2. Assessing the Accuracy of the Coefficient Estimates p63
  - 3.1.3. Assessing the Accuracy of the Model p68
- 3.2. Mulitple Linear Regression p71
  - 3.2.1. Estimating the Regression Coefficients p72
  - 3.2.2. Some Important Questions p75
- 3.3. Other Considerations in the Regression Model p82
  - 3.3.1. Qualitative Predictors p82
  - 3.3.2. Extensions of the Linear Model p86
  - 3.3.3. Potential Problems p92
- 3.4. The Marketing Plan p102
- 3.5. Comparison of Linear Regression with K-Nearest Neighbors p104
- 3.6. Lab: Linear Regression p109
  - 3.6.1. Libraries p109
  - 3.6.2. Simple Linear Regression p110
  - 3.6.3. Multiple Linear Regression p113
  - 3.6.4. Interaction Terms p115
  - 3.6.5. Non-linear Transformations of the Predictors p115
  - 3.6.6. Qualitative Predictors p119
  - 3.6.7. Writing Functions p119
- 3.7. Exercises p120

#### 4. Classifiction 
- 4.1. An Overview of Classification p128
- 4.2. Why Not Linear Regression? 129
- 4.3. Logistic Regression p130
  - 4.3.1. The Logistic Model p131
  - 4.3.2. Estimating the Regression Coefficients p133
  - 4.3.3. Making Predictions p134
  - 4.3.4. Multiple Logistic Regression p135
  - 4.3.5. Logistic Regression for > 2 Response Classes
- 4.4. Linear Discriminant Analysis p138
  - 4.4.1. Using Bayes' Theorem for Classification p138
  - 4.4.2. Linear Discriminant Analysis for p = 1 p139
  - 4.4.3. Linear Discriminant Analysis for p > 1 p142
- 4.5. A Comparison of Classification Methods p151
- 4.6. Lab: Logistic Regression, LDA, QDA, and KNN p154
  - 4.6.1. The Stock Market Data p154
  - 4.6.2. Logistic Regression p156
  - 4.6.3. Linear Discriminant Analysis p161
  - 4.6.4. Quadratic Discriminant Analysis p163
  - 4.6.5. K-Nearest Neighbors p163
  - 4.6.6. An Application to Caravan Insurance Data p165
- 4.7. Exercises p168

#### 5. Resampling Methods 
- 5.1. Cross-Validation p176
  - 5.1.1. The Validation Set Approach p176
  - 5.1.2. Leave-One-Out Cross-Validation p178
  - 5.1.3. k-Fold Cross-Validation p181
  - 5.1.4. Bias-Variance Trade-Off for k-Fold Cross Validation p183
  - 5.1.5. Cross-Validation on Classification Problems p184
- 5.2. The Bootstrap p187
- 5.3. Lab: Cross-Validation and the Bootstrap p190
  - 5.3.1. The Validation Set Approach p191
  - 5.3.2. Leave-One-Out Cross Validation p192
  - 5.3.3. k-Fold Cross Validation p193
  - 5.3.4. The Bootstrap p194
- 5.4. Exercises p197

#### 6. Linear Model Selection and Regularization 203
- 6.1. Subset Selection p205
  - 6.1.1. Best Subset Selection p205
  - 6.1.2. Stepwise Selection p207
  - 6.1.3. Choosing the Optimal Model p210 
- 6.2. Shrinkage Methods p214
  - 6.2.1. Ridge Regression p215
  - 6.2.2. The Lasso p219
  - 6.2.3. Selecting the Tuning Parameter p227
- 6.3. Dimension Reduction Methods p228
  - 6.3.1. Principal Component Regression p230
  - 6.3.2. Partial Least Squares p237
- 6.4. Consideratons in High Dimensions p238
  - 6.4.1. High-Dimensional Data p238
  - 6.4.2. What Goes Wrong in High Dimensions? p239
  - 6.4.3. Regression in High Dimensions p241
  - 6.4.4. Interpreting Results in High Dimensions p243
- 6.5. Lab 1: Subset Selection Methods p244
  - 6.5.1. Best Subset Selection p244
  - 6.5.2. Forward and Backward Stepwise Selection 247
  - 6.5.3. Choosing Among Models Using the Validation Set Approach and Cross-Validation p248
- 6.6. Ridge Regression and the Lasso p251
  - 6.6.1. Ridge Regression p251
  - 6.6.2. The Lasso p255
- 6.7. PCR and PLS Regression p256
  - 6.7.1. Principal Components Regression p256
  - 6.7.2. Partial Least Squares p258
- 6.8. Exercises p259

#### Moving Beyond Linearity 265
- 7.1. Polynomial Regression p266
- 7.2. Step Functions p268
- 7.3. Basis Functions p270
- 7.4. Regresson Splines p271
  - 7.4.1. Piecewise Polynomials p271
  - 7.4.2. Contraints and Splines p271
  - 7.4.3. The Spline Basis Representation p273
  - 7.4.4. Choosing the Number and Locations of the Knots p274
  - 7.4.5. Comparison to Polynomial Regression p276
- 7.5. Smoothing Splines 277
  - 7.5.1. An Overview of Smoothing Splines 277
  - 7.5.2. Choosing the smoothing parameter lambda  p278
- 7.6. Local Regression p282
- 7.7. Generalized Additive Models p282
  - 7.7.1. GAMs for Regression Problems p283
  - 7.7.2. GAMs for Classification Problems p286 
- 7.8. Lab: Non-linear Modeling p287
  - 7.8.1. Polynomial Regression and Step Functions 288
  - 7.8.2. Splines p293
  - 7.8.3. GAMs p294
- 7.9. Exercises p297

#### 8 Tree-Based Methods 
- 8.1. The Basis of Decision Trees p303
  - 8.1.1. Regression Trees p304
  - 8.1.2. Classification Trees p311
  - 8.1.3. Trees Versus Linear Models p314
  - 8.1.4. Advantages and Disadvantages of Trees p315
- 8.2. Bagging, Random Forests, Boosting p316
  - 8.2.1. Bagging p316
  - 8.2.2. Random Forests p320
  - 8.2.3. Boosting p321
- 8.3. Lab: Decision Trees p324
  - 8.3.1. Fitting Classificaton Trees p324
  - 8.3.2. Fitting Regression Trees p327
  - 8.3.3. Bagging and Random Forests p328
  - 8.3.4. Boosting p330
- 8.4. Exercises p332

#### 9. Support Vector Machines p337
- 9.1. Maximal Margin Classifier p338
  - 9.1.1. What is a Hyperplane? p338
  - 9.1.2. Classification Using a Separating Hyperplane? p339
  - 9.1.3. The Maximal Margin Classifier p341
  - 9.1.4. Construction of the Maximal Margin Classifier p342
  - 9.1.5. The Non-seperable Case p343
- 9.2. Support Vector Classifiers p344
  - 9.2.1. Overview of the Support Vector Classifier p344
  - 9.2.2. Details of the Support Vector Classifier p345
- 9.3. Support Vector Machines p349
  - 9.3.1. Classification with Non-Linear Decision Boundaries p349
  - 9.3.2. The Support Vector Machine p350
  - 9.3.3. An Application to Heart Disease Data p354
- 9.4. SVMs with More than Two Classes p355
  - 9.4.1. One-Versus-One Classification p355
  - 9.4.2. One-Versus-All Classification p356
- 9.5. Relationship to Logistic Regression p356
- 9.6. Lab: Support Vector Machines p359
  - 9.6.1. Support Vector Classifier p359
  - 9.6.2. Support Vector Machine p363
  - 9.6.3. ROC Curves p365
  - 9.6.4. SVM with Multiple Classes p366
  - 9.6.5. Application to Gene Expression Data p366
- 9.7. Exercises p368

#### 10 Unsupervised Learning 
- 10.1. The Challenge of Unsupervised Learning p373
- 10.2. Principal Components Analysis p374
  - 10.2.1. What are Principal Components? p375
  - 10.2.2. Another Interpretation of Principal Components p379
  - 10.2.3. More on PCA p380
  - 10.2.4. Other Uses for Principal Components p385
- 10.3. Clustering Methods p385
  - 10.3.1. K-Means Clustering p386
  - 10.3.2. Hierarchical Clustering 390
  - 10.3.3. Practical Issues in Clustering p399
- 10.4. Lab 1: Principal Component Analysis P401
- 10.5. Lab 2: Clustering 
  - 10.5.1. K-Means Clustering 404
  - 10.5.2. Hierarchical Clustering 406
- 10.6. Lab 3: NCI60 Data Example 
  - 10.6.1. PCA on the NCI60 Data 
  - 10.6.2. Clustering the Observations of the NCI60 Data
- 10.7. Exercises p413
  