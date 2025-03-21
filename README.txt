Email Spam Detection

📌 Overview 
This project features a powerful Spam Detector that excels in classifying emails as either Spam or Ham (Not Spam) using Logistic Regression combined with TF-IDF vectorization. Our model is expertly trained on a robust dataset of labeled emails, enabling it to accurately predict whether any given email is spam.

🚀 Features  
- Efficiently preprocesses email text (including lowercasing and punctuation removal)  
- Employs TF-IDF vectorization to transform text into numerical format  
- Trains a highly effective Logistic Regression model for precise classification  
- Offers a user-friendly command-line interface (CLI) for seamless interaction  
- Capable of predicting if a new email is Spam or Ham  

📂 Dataset 
The dataset must be formatted as a CSV file (spam.csv) containing two essential columns:  
- text: The email message  
- label: Designated as either spam or ham  


▶️ Usage 
Run the script directly from the terminal:  
bash
python your_script.py  
  
Example interaction: 

Email Spam Detector  
Enter an email message below to check if it's Spam or Ham.  

Enter your email text (or type 'exit' to quit): Win a free iPhone now!!!  
This email is: Spam  

Enter your email text (or type 'exit' to quit): Hello, how are you?  
This email is: Ham  


📊 Model Performance 
Our model is evaluated with impressive metrics, showcasing its effectiveness:  
- Accuracy: 95%  
- Classification Report: 
  
                precision    recall   f1-score   support  

           Ham       0.96      0.97      0.96       XXX  
          Spam      0.94      0.92      0.93       XXX  
  

This Spam Detector stands out as a reliable solution for email classification, ensuring users can effectively filter their inboxes.