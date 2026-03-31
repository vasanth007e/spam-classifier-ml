**Spam Message Classifier:**
This project is a machine learning model that classifies SMS messages as Spam or Ham (Not Spam).
Features:
	Text preprocessing using TF-IDF,
	Classification using Naive Bayes,
	Achieves ~96% accuracy,
	Custom message prediction support

**Technologies Used:**
	Python,
	Pandas,
	Scikit-learn
	
**Workflow:**
	Load dataset,
	Clean and preprocess data,
	Convert text to numerical features (TF-IDF),
	Train model (Naive Bayes),
	Evaluate model,
	Test with custom input

**Example:**
		predict_spam("Free entry in a weekly contest")

**Result:**
	Accuracy: ~96%,	
	Model can classify real-time messages	

**Limitations:**
	Depends on training data,
	May misclassify unseen patterns	
