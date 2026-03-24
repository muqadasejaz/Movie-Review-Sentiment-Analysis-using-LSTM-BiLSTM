# Movie Review Sentiment Analysis using LSTM & BiLSTM

## Project Overview
This project performs **sentiment analysis** on movie reviews from the IMDB dataset using deep learning techniques. The goal is to classify user feedback as **positive** or **negative** based on the textual content of reviews. Two models are implemented: **LSTM** and **BiLSTM**, to compare their performance in understanding sequential data.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Objectives
- Analyze IMDB movie reviews to detect sentiment.
- Implement **LSTM** and **BiLSTM** models for sentiment classification.
- Compare model performance and evaluate prediction accuracy.
- Provide insights into model training through visualizations such as accuracy and loss curves.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Features
- Text preprocessing including tokenization and padding.
- Sentiment classification into positive or negative categories.
- Performance evaluation with accuracy, loss, and confusion matrix.
- Comparison between LSTM and BiLSTM models.
- Prediction on new reviews to test the model.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn  
- **IDE:** Jupyter Notebook / VS Code  
- **Dataset:** IMDB Movie Reviews (Kaggle)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Dataset
The dataset is available on Kaggle: [IMDB Data](https://www.kaggle.com/datasets/mahmoudshaheen1134/imdp-data)  

**Columns:**
- `review`: The text of the movie review  
- `sentiment`: The sentiment label (positive/negative)  

**Feedback Type:** User review  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Model Details
| Model   | Training Accuracy |
|---------|-----------------|
| LSTM    | 97%             |
| BiLSTM  | 99%             |

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Model Performance

## LSTM

### Training vs Validation Accuracy & Training vs Validation Loss
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/d7105b45-dce1-4da7-a519-1ea691bb412d" />


### Confusion Matrix 
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/6d2d59e8-086b-4616-b313-61cd1fb7d678" />

## BiLSTM

### Training vs Validation Accuracy & Training vs Validation Loss
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/ba0b027d-e9af-4d8f-849c-6424ed6e5004" />

### Confusion Matrix
<img width="522" height="470" alt="image" src="https://github.com/user-attachments/assets/8186f09b-d742-4ab3-8d44-45b59fa459bb" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Results & Predictions
- Both models show high performance, with BiLSTM slightly outperforming LSTM.  
- The trained models can predict the sentiment of new movie reviews effectively.  

**Example Predictions:**
| Review                                      | Predicted Sentiment |
|---------------------------------------------|------------------|
| "Amazing movie with fantastic acting!"      | Positive         |
| "The plot was boring and predictable."     | Negative         |

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Conclusion
This project demonstrates the power of **LSTM** and **BiLSTM** in handling sequential text data for sentiment analysis. BiLSTM, with its ability to consider context from both directions, achieves higher accuracy and provides more reliable predictions for movie reviews.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Future Work
- Experiment with **attention mechanisms** to improve performance.
- Extend the model to handle **multi-class sentiment analysis**.
- Deploy the model in a **web or mobile application** for real-time predictions.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## References
- Kaggle Dataset: [IMDB Data](https://www.kaggle.com/datasets/mahmoudshaheen1134/imdp-data)  
- TensorFlow Documentation: [https://www.tensorflow.org](https://www.tensorflow.org)

## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

AI/ML Engineer

Data Science & Gen AI Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

📬 Kaggle: [Kaggle Profile](https://www.kaggle.com/muqaddasejaz) 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
