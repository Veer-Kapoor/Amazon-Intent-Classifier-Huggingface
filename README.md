# Amazon Intent Classifier

### Hugging Face + Gradio AI Deployment

This project demonstrates how a trained text classification model can be deployed as an interactive AI application using **Hugging Face Spaces and Gradio**.

The application classifies customer queries related to Amazon services and predicts the user's intent.

The project explores how AI models can power **customer support automation** through natural language understanding.

---

# Live Applications

### Hugging Face Profile

https://huggingface.co/Veerkapoor

---

### Main Application

https://huggingface.co/spaces/Veerkapoor/hosting-amazon-model-gradio

This Hugging Face Space hosts the deployed AI application built using **Gradio**.

---

### Alternative Deployment

https://huggingface.co/spaces/Veerkapoor/hosting-amazon-model-gradio-mymodel

This version demonstrates another deployment environment for the same model.

---

# Application Demo

### Intent Classification Interface

![Intent Classifier UI](assets/screenshots/gradio-ui.png)

Users can input customer queries such as:

```
where is my order?
```

The model predicts the **intent category** of the message.

Example output:

```
order_status
```

---

### Chatbot Interaction

![Chatbot Interface](assets/screenshots/chatbot-ui.png)

The chatbot interface simulates a customer support assistant capable of responding to user queries related to Amazon orders.

---

### Hugging Face Spaces Deployment

![Hugging Face Spaces](assets/screenshots/huggingface-spaces.png)

The application is deployed using **Hugging Face Spaces**, which provides a simple way to host machine learning applications publicly.

---

# System Workflow

The system processes customer queries through the following pipeline:

```
User Query
     ↓
Gradio Interface
     ↓
Text Classification Model
     ↓
Intent Prediction
     ↓
Customer Support Response
```

---

# Project Setup Process

The application was deployed using the following workflow:

1. Create a Hugging Face Space
2. Select **Gradio** as the interface framework
3. Configure the environment
4. Upload the trained model
5. Deploy the application publicly

The space was created as a **public Gradio workspace to host the trained Amazon model**. 

---

# Key Learnings

Through this project the following concepts were explored:

* Deploying AI models using Hugging Face Spaces
* Building interactive machine learning applications with Gradio
* Hosting AI applications publicly
* Understanding text classification workflows
* Designing AI-powered customer support systems

---

# Author

**Veer Kapoor**
AI Product Management | AI Experiments
