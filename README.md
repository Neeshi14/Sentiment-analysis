#  Sentiment Analysis using RNN (LSTM)  
This project performs **sentiment analysis** on movie and TV show reviews using an RNN-based LSTM model. The objective is to classify reviews as **positive** or **negative** based on the textual content.

---

##  Dataset: IMDB Reviews

These is the dataset link [here](https://www.kaggle.com/code/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews  ).

The dataset contains two main columns:

| Column    | Description                                   |
|-----------|-----------------------------------------------|
| `Reviews` | Text reviews (e.g., dialogues from movies/series) |
| `Sentiment` | Label indicating sentiment: `positive` or `negative` |

---

##  Project Workflow

###  Step 1: Importing the Dataset
- Loaded the IMDB dataset for training and testing.

###  Step 2: Text Preprocessing
- Cleaned the reviews by:
  - Lowercasing
  - Removing special characters
  - Tokenizing and padding sequences
- Used word embeddings for converting text into numerical form.

###  Step 3: Building the LSTM Model
- Implemented a **Recurrent Neural Network (RNN)** using **Long Short-Term Memory (LSTM)** layers.
- Designed a model suitable for binary classification tasks.

###  Step 4: Model Evaluation
- Evaluated the model using accuracy as the key metric.

---

##  Model Performance

| Metric               | Score    |
|----------------------|----------|
| **Training Accuracy**| 98%      |
| **Testing Accuracy** | 86%      |

---

##  Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NLP preprocessing**: `nltk`, `re`, `Tokenizer`
- **Word Embeddings**:  Embedding layer
- **LSTM** for sequence learning

---

##  Conclusion

This project demonstrates the use of **LSTM-based deep learning** for analyzing sentiment in movie and TV show reviews. The model achieved:
- ** Training accuracy (98%)**
- ** Test accuracy (86%)**

This indicates the model is effectively learning patterns and performing well on unseen data.



