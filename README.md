Computational pipeline to discriminate between non-malignant and malignant tumor papillary thyroid cancer samples from The Cancer Genome Atlas (TCGA) using classical statistic and random forest approaches

## How to use
The code is executed within Google Collaboratory (Colab), where it is not necessary to install or download, however, to ensure proper functioning, it must be executed in an orderly manner, starting with the first block.

To run the code, you need to access the root file (PredictiveModelInTumorSamplesUsingArtificialIntelligence.ipynb) and click on “Open in Colab”, using Github's “Preview” mode.

## Phases
- Directory choice
- Data import (TCGA)
- Separation of samples into single and paired
- Descriptive statistics and graph generation
- Data selection (Grouping and removing samples)
- Boxplot by tumor type
- Descriptive statistics and statistical analysis of paired samples
- Selection of relevant tumor types for machine learning application
- Simplified boxplot of relevant tumor types
- Application of machine learning (simple hold-out or with validation group)
- ROC curve
- Heatmaps (Accuracy, Precision, Recall and F1-score)

## Example
In the heatmap (Accuracy) below, we can observe the results obtained through the application of the model (Simple Hold-out) in different tumor types.

![accuracy-heatmap](https://github.com/CleitonValandro/predictive-model-in-tumor-samples-using-artificial-intelligence/assets/54510844/371e5ab1-d938-4378-9bdc-8f861fad9ce4)
