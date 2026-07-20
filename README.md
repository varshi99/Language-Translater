#  Language Translation Bot using Amazon Lex

## 📌 Project Overview

The Language Translation Bot is a cloud-based chatbot built using AWS services. It enables users to translate text between multiple languages through a conversational interface. The chatbot is powered by Amazon Lex and AWS Lambda, providing a serverless and scalable solution for language translation.

This project demonstrates how AWS AI and serverless services can be integrated to build an intelligent chatbot application.

---

## 🚀 Features

- Translate text between multiple languages
- Conversational chatbot using Amazon Lex
- Serverless backend with AWS Lambda
- Fast and scalable cloud architecture
- Easy deployment on AWS
- Simple and user-friendly interaction

---

## 🛠️ AWS Services Used

- Amazon Lex
- AWS Lambda
- Amazon Translate
- AWS IAM

---

## 💻 Technologies Used

- Python
- AWS SDK (Boto3)
- Amazon Lex
- AWS Lambda
- Amazon Translate

---

## 🏗️ Project Architecture

```text
User
   │
   ▼
Amazon Lex
   │
   ▼
AWS Lambda
   │
   ▼
Amazon Translate
   │
   ▼
Translated Response
```

---

## 📂 Project Structure

```
Language-Translation-Bot/
│
├── lambda_function.py
├── README.md
└── requirements.txt (if applicable)
```

---

## ⚙️ Setup Instructions

### 1. Create an Amazon Lex Bot

- Open AWS Console
- Navigate to Amazon Lex
- Create a new bot
- Configure intents and slots
- Connect the Lambda function

### 2. Deploy Lambda Function

- Create a Lambda function
- Upload `lambda_function.py`
- Attach the required IAM permissions
- Configure the Amazon Translate API access

### 3. Test the Chatbot

- Open Amazon Lex Test Console
- Enter text in one language
- Receive the translated response

---

## 📸 Example

**Input**

```
Translate "Hello, how are you?" to Spanish
```

**Output**

```
Hola, ¿cómo estás?
```

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- Amazon Lex
- AWS Lambda
- Amazon Translate
- Serverless Computing
- Cloud-based AI Applications
- AWS IAM
- Event-driven Architecture

---

## 📈 Future Enhancements

- Voice input support
- Speech-to-Speech translation
- Translation history
- User authentication with Amazon Cognito
- Store translations in Amazon DynamoDB
- Deploy a web interface using Amazon S3 and CloudFront

---

## 👩‍💻 Author

**Varshitha Pavuluri**

GitHub: https://github.com/varshi99

LinkedIn: https://www.linkedin.com/in/pavuluri-varshitha-093960244/


---

## 📄 License

This project is intended for learning and educational purposes. If this repository is based on or adapted from another open-source project, please retain any attribution and comply with the original project's license.
