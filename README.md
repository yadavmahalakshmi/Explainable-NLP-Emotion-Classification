# Explainable-NLP-Emotion-Classification
An explainable NLP system that performs multi-label emotion classification on the GoEmotions dataset using DistilBERT and provides LIME and Integrated Gradients explanations for model predictions.

## Project Overview
This project focuses on multi-label emotion classification using Natural Language Processing (NLP). 
The system uses the GoEmotions dataset and a fine-tuned DistilBERT model to identify multiple emotions expressed in a given text.
Since transformer-based models can be difficult to interpret, Explainable AI (XAI) techniques are integrated into the project. 
LIME and Integrated Gradients are used to explain which words contribute to the model's emotion predictions.
The project also includes model evaluation using classification metrics, visualization techniques, and explanation-quality measures such as comprehensiveness and sufficiency.

## Objectives
- To develop a multi-label emotion classification system using NLP.
- To fine-tune DistilBERT for emotion classification.
- To classify multiple emotions that may be present in a single text.
- To provide understandable explanations for model predictions.
- To use LIME and Integrated Gradients for model interpretability.
- To evaluate the model using precision, recall, and F1-score.
- To analyze model performance using ROC curves, Precision-Recall curves, and confusion matrices.
- To evaluate the quality of explanations using comprehensiveness and sufficiency.

## Tools & Technologies
- **Programming Language:** Python
- **NLP:** Natural Language Processing
- **Model:** DistilBERT
- **Dataset:** GoEmotions
- **Machine Learning:** Scikit-learn
- **Explainable AI:** LIME, Integrated Gradients
- **Visualization:** Plotly
- **Web Interface:** Gradio
- **Development Environment:** Jupyter Notebook

## Explanation Methods
### LIME
LIME (Local Interpretable Model-Agnostic Explanations) explains individual predictions by identifying the words that have the greatest influence on the model's prediction.

### Integrated Gradients
Integrated Gradients is a gradient-based explanation method that measures the contribution of input tokens to the model's prediction.
Both methods help make the DistilBERT predictions more understandable and provide insight into why particular emotions were predicted.

## Evaluation
The model is evaluated using the following measures:
- **Precision** – Measures how many predicted positive emotions are correct.
- **Recall** – Measures how many actual emotions are correctly identified.
- **F1-Score** – Provides a balance between precision and recall.
- **ROC Curves** – Used to analyze classification performance across different thresholds.
- **Precision-Recall Curves** – Used to evaluate performance, particularly for imbalanced emotion classes.
- **Confusion Matrices** – Used to analyze classification errors between emotion classes.
- **Comprehensiveness** – Measures how much the prediction changes when important features identified by the explanation are removed.
- **Sufficiency** – Measures whether the important features identified by the explanation are sufficient to retain the model's prediction.

## Dataset
The project uses the **GoEmotions dataset**, developed by Google Research.
The dataset contains Reddit comments annotated with emotions and is suitable for multi-label emotion classification.
