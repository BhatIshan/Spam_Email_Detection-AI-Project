# 📨 Spam Email Detection using Naive Bayes

This project aims to detect spam emails using a Naive Bayes classifier. It processes a dataset of labeled emails and learns to classify incoming messages as **spam** or **not spam** based on the frequency of words.

## 🧠 Project Overview

- **Algorithm Used**: Gaussian Naive Bayes
- **Accuracy Achieved**: ~96.5%
- **Technology Stack**: Python, NumPy, scikit-learn, basic NLP
- **Developed by**: Ishan Bhat

The model is trained on a labeled dataset of 702 emails and tested on 260 emails. The most common 3000 words across all emails are used as features to build a frequency matrix for classification.

## 🛠️ Features

- Text preprocessing
- Word frequency extraction
- Feature matrix construction
- Spam classification using Naive Bayes
- Model evaluation using accuracy score

## 📁 Project Structure

```
├── train-mails/         # Training email files
├── test-mails/          # Testing email files
├── Naive_Bayes_Model.ipynb  # Main Jupyter Notebook
├── README.md            # Project overview
```

## 📊 Sample Results

- **Training Accuracy**: ~96.5%
- **Confusion Matrix**: [You can add a screenshot if available]
- **Prediction Output**: Labels generated for each test email

## 📚 Dataset Info

- Each email is a `.txt` file.
- The **first line** contains the subject, and the **third line** contains the message body.
- Files starting with `spmsg` are labeled as **spam**, others as **non-spam**.

> Note: This project is based on a public academic example. Adaptations, cleaning, and modifications were done by Ishan Bhat as part of a capstone AI project.

## 🧑‍💻 Author

**Ishan Bhat**  
Department of Information Science  
NMAM Institute Of Technology Nitte  
Email: isbhat235@gmail.com

## ⚖️ License

This project is intended for academic and learning purposes only. Attribution is given to the original reference project upon which this implementation was based.

## 📌 Acknowledgments

- Inspired by publicly available spam detection examples and adapted for educational use.
- scikit-learn documentation  
- UCI SMS Spam Dataset (if added)
