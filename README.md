# Non-Functional-Requirements-Classication

An automated classification system that distinguishes between Functional and Non-Functional Requirements (NFRs) such as Security and Reliability. This project implements a variety of Machine Learning models and a Deep Learning Fusion CNN to achieve high-accuracy requirement engineering.🚀 Key FeaturesMultiple Embedding Techniques: Supports Term Frequency (TF), TF-IDF, and Word2Vec.Hybrid Model Architecture: Includes SVM, Naive Bayes, Logistic Regression, and a custom Convolutional Neural Network (CNN).Fusion CNN: A high-performance model achieving near 100% accuracy on specific datasets by merging feature embeddings.Interactive GUI: Built with Tkinter for easy dataset loading, model training, and results visualization.Comprehensive Metrics: Automatically generates Precision, Recall, F1-Score, and Accuracy comparisons.📊 Performance ComparisonBased on the output.html results, here is how the models stack up:AlgorithmFeature SetPrecisionRecallAccuracyFusion CNNTF-IDF100.0%100.0%100.0%CNNTF-IDF98.5%99.8%99.75%Logistic RegressionTF-IDF88.7%85.5%96.25%SVMTF-IDF91.2%61.9%93.5%🛠️ Installation & SetupClone the repository:Bashgit clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
Install dependencies:Bashpip install numpy pandas matplotlib nltk sklearn tensorflow keras gensim
Download NLTK Data:The project requires specific NLTK resources for preprocessing:Pythonimport nltk
nltk.download('stopwords')
nltk.download('wordnet')
💻 How to RunSimply execute the batch file (Windows):Bashrun.bat
Or run the main script directly:Bashpython NonFunctionalRequirement.py
📂 Project StructureNonFunctionalRequirement.py: The main GUI application logic.cnn.py: Contains the deep learning model architecture and training loops.Pure_Annotate_Dataset.csv: The primary labeled dataset for training.output.html: A generated report summarizing the performance of all tested algorithms.
