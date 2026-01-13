# Task 1: News Category Classifier (BERT)

## 🎯 Objective
The goal of this project is to fine-tune a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model to accurately classify news headlines into four distinct categories: World, Sports, Business, and Sci/Tech.

## 🛠️ Technical Implementation
* **Model:** `bert-base-uncased` from the Hugging Face Transformers library.
* **Dataset:** AG News Dataset (Title-based classification).
* **Optimization:** Fine-tuned using the `Trainer` API with a custom PyTorch Dataset class.
* **Deployment:** Created a live, interactive web interface using **Gradio** for real-time headline testing.



## 🚀 Key Insights
* **Contextual Understanding:** Unlike traditional TF-IDF models, BERT understands the relationship between words in a headline, leading to higher accuracy.
* **Transfer Learning:** By using a pre-trained model, we achieved professional-grade results with only 1 epoch of training.
* **Accessibility:** The Gradio deployment makes the AI model usable for non-technical users via a browser link.
