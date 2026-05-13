Spam Email Classifier using Naive Bayes
A machine learning project to classify emails as Spam or Ham (Not Spam) using the Multinomial Naive Bayes algorithm. This project demonstrates text preprocessing, feature extraction with CountVectorizer, and model evaluation using accuracy and confusion matrix.

📊 Dataset
The dataset contains email messages with two columns:

label: Spam or Ham

text: Email content

Shape: 193,852 rows × 2 columns

🛠️ Technologies Used
Python 3.13

Pandas – Data manipulation

Scikit-learn – Machine learning & text vectorization

Jupyter Notebook – Development environment

🔧 Steps Performed
Data Loading – Loaded CSV file containing email messages

Data Cleaning – Removed null values from the dataset

Label Encoding – Converted 'Spam'/'Ham' to numerical values (1/0) using LabelEncoder

Train-Test Split – Split data into 75% training and 25% testing

Text Vectorization – Used CountVectorizer with English stop words

Model Training – Trained MultinomialNB classifier

Prediction & Evaluation – Generated predictions and evaluated using confusion matrix and accuracy score

Custom Prediction – Tested model with a custom email message

📈 Model Performance
text
Confusion Matrix:
[[25293   330]
 [ 1591 21249]]

Accuracy Score: 0.9603 (96.03%)
🧪 Example Prediction
The model successfully classifies promotional/lottery emails as Spam with high accuracy.

📁 Project Structure
text
├── spam_Emails_data.csv      # Dataset file
├── hamspam.ipynb              # Jupyter Notebook with complete code
└── README.md                  # Project documentation
🚀 How to Run
Clone the repository

Install dependencies:

bash
pip install pandas scikit-learn
Run the Jupyter Notebook:

bash
jupyter notebook hamspam.ipynb
📌 Results
The Naive Bayes classifier achieved 96% accuracy in distinguishing spam emails from legitimate ones, demonstrating effectiveness for text classification tasks with high-dimensional sparse data.

👨‍💻 Author

Krishna_Great
