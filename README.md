# -LSTM-And-GRU-End-To-End-Deep-Learning-Project--Predicting-Next-Word

# Next Word Prediction Using LSTM Networks  

## Project Overview  
This project focuses on developing a deep learning model to predict the next word in a given sequence of words. The model is built using **Long Short-Term Memory (LSTM) networks**, which are highly effective for sequence prediction tasks.  

##  Project Workflow  
The project follows these key steps:  

### 1 Data Collection  
- The dataset is sourced from **Shakespeare’s *Hamlet***, a rich and complex text that provides a challenging testbed for the model.  

### 2️ Data Preprocessing  
- The text data undergoes **tokenization, sequence generation, and padding** to ensure uniform input lengths.  
- The sequences are divided into **training and testing sets**.  

### 3️ Model Building  
- The LSTM-based model consists of:  
  - **Embedding Layer** for word representation.  
  - **Two LSTM Layers** to capture sequential patterns.  
  - **Dense Output Layer** with a **softmax activation** function to predict the probability of the next word.  

### 4️ Model Training  
- The model is trained on the preprocessed sequences.  
- **Early stopping** is implemented to prevent overfitting by monitoring validation loss and stopping training when improvements cease.  

### 5️ Model Evaluation  
- The trained model is assessed using example sentences to gauge its accuracy in predicting the next word.  

### 6️ Deployment  
- A **Streamlit web application** is developed to allow users to input a sequence of words and get real-time next-word predictions.  

---
  

