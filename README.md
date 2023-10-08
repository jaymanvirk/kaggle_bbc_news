### BBC News articles classification: Non-negative Matrix Factorization vs Supervised Learning.

#### Abstract
This study presents a fraction of an analysis of a BBC News dataset, encompassing Exploratory Data Analysis (EDA) and preprocessing stages, followed by a performance comparison of Non-Negative Matrix Factorization (NMF) against various supervised learning (SL) algorithms. The dataset comprises articles' texts and their categories: business, sport, tech, politics and entartainment.

The results of this study showed that SL algorithms such as SVM and Random Forest (RF) scored better than NMF in terms of accuracy, but were completely outperformed by NMF in terms of computational speed.

Additionally the NMF provided surprising results, when on every sample size, 50%, 20% and 10% of the train dataset, it provided test scores on par with the its train scores. SVM and RF models while resulting in higher accuracy than NMF across sample sizes, got more prominent overfitting problem with the data size reduction.

The presented stages in this project are supposed to provide insights into how to run EDA, preprocess data and finally the suitability of NMF as a dimensionality reduction method compared to traditional supervised learning algorithms. This notebook serves as a light guide for data science enthusiasts aiming to tackle similar tasks.
