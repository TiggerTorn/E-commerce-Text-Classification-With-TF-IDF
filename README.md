# E-commerce-Text-Classification-With-TF-IDF


## Project Overview
This project focuses on text classification within the e-commerce sector by leveraging the TF-IDF (Term Frequency-Inverse Document Frequency) technique. The goal is to categorize product descriptions into four primary categories: **Electronics, Household, Books, and Clothing & Accessories**. By automating this classification, the project aims to enhance product tagging, streamline user experience, and improve search engine performance on e-commerce platforms.

## Dataset
The dataset used in this project was sourced from various Indian online shopping platforms and includes:
- Product descriptions and corresponding categories in CSV format.
- Four categories:
  - **Electronics**
  - **Household**
  - **Books**
  - **Clothing & Accessories**
- Pre-processing steps involved reorganizing the dataset for efficient analysis.

## Methodology
### 1. **Text Normalization**
The project applied an 11-step text normalization process, which included:
- Converting text to lowercase
- Removing whitespaces, punctuations, and non-alphabetic words
- Substituting acronyms and contractions
- Applying stemming and lemmatization

### 2. **TF-IDF Vectorization**
TF-IDF was employed to transform product descriptions into numerical vectors, representing the importance of words relative to the overall dataset.

### 3. **Machine Learning Models**
Five models were trained and evaluated for classification:
- **Linear SVM (Support Vector Machine)**
- **Logistic Regression**
- **Random Forest**
- **KNN Classifier**
- **Decision Tree**

### 4. **Performance Evaluation**
The models were evaluated based on training and validation accuracy:
- **Linear SVM** showed the best performance with:
  - **Training Accuracy**: 97.8%
  - **Validation Accuracy**: 95.3%
- **Logistic Regression** also performed well with 94.4% validation accuracy.

Hyperparameter tuning was applied to optimize the performance of the best model, leading to a final test accuracy of **95.04%**.

## Results
The confusion matrix analysis revealed strong classification capabilities, with high true positive rates across all categories. Some misclassifications were noted, particularly between categories like 'Books' and 'Household', suggesting areas for further improvement.

## Conclusion
This project successfully demonstrates the potential of using TF-IDF combined with machine learning for efficient product categorization in the e-commerce domain. The implementation highlights the importance of text normalization and model selection to achieve high classification accuracy.



## References
[1] A. Krishnan and A. Amarthaluri, “Large Scale Product Categorization using Structured and Unstructured Attributes,” 2019, [Online]. Available: https://ar5iv.labs.arxiv.org/html/1903.04254

[2] .H. Jahanshahi, O. Ozyegen, M. Cevik, B. Bulut, D. Yigit, and F. Gonen, “Text Classification for Predicting Multi-level Product Categories,” 2022, [Online]. Available: https://ar5iv.labs.arxiv.org/html/2109.01084

[3] S. Ghosh, “E-commerce Text Classification (TF-IDF + Word2Vec),” 2023, [Online]. Available: https://www.kaggle.com/code/sugataghosh/e-commerce-text-classification-tf-idf-word2vec#Word2Vec-Model

[4] N. Sidelnikov, “Machine Learning in eCommerce Product Categorization,” 2020, [Online]. Available: https://virtocommerce.com/blog/ecommerce-product-categorization
