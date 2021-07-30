# Spam-Detection-with-Transfomers
This project used a combination of feature engineering and BERT to achieve an F1 score of 0.97 in predicting spam: https://github.com/chingfhen/Spam-Detection-with-Transfomers/blob/main/notebooks/7.%20Comparing%20the%20performances%20of%20different%20techniques%20and%20models.ipynb

Insights:
  1. Fine tuning on **paraphrased spam may hurt performance** because the paraphrased emails may have their meaning altered detrimentally
  2. **Concatenating engineered features as input text further improves performance of BERT!**
