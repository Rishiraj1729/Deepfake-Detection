Deep Fake Detection
Deepfakes have been prominent in the online world for many years now and there are state-of-the-art models that successfully predict the fake faces from the real faces. However, those models use deep neural network and are computationally expensive. This approach using simple machine learning algorithms to detect deepfakes within an image using its frequency spectrum. It has been seen that deepfakes deviate from the real images when viewed in the frequency domain. This deviation is then used and put through different machine learning classifiers and see how well every algorithm performs.

Dataset used:
Real faces: CelebA dataset (10,000 images)
Fake faces: 100K fake dataset (10,000 images)

Six different machine learning algorithms were used in a pipeline and their performance were measured using their and accuracy and AUC. Below are the results of the pipeline using all 10,000 images.

Model	Accuracy	AUC
Logistic Regression	100%	1.00
SVM	99.7%	1.00
KNN	99.85%	1.00
Decision Tree	99.8%	1.00
Random Forest	99.95%	1.00
Naive Bayes	92.35%	0.95
