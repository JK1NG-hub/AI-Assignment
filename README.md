# AI-Assignment
This notebook aims to analyze credit card transaction data for potential fraud detection. The dataset includes features such as 'distance_from_home', 'distance_from_last_transaction', 'ratio_to_median_purchase_price', and transaction types like 'used_pin_number', 'used_chip', and 'online_order'. The main objective is to identify fraudulent transactions and evaluate different models that help with detecting fraud.
### Analysis Goals
Explore the dataset to understand the distribution of features and their relationship with fraud.

Visualize key insights such as the impact of transaction distance and median purchase price on fraud likelihood.

Build and evaluate models: A baseline "Never Fraud" model that assumes no transaction is fraudulent. A k-Nearest Neighbors (k-NN) model to classify transactions as fraudulent or non-fraudulent.

Compare the performance of these models using metrics like accuracy, precision, recall, and F1-score.


### How AI Was Used to Assist

AI, specifically OpenAI's ChatGPT, was used throughout this project to streamline the development process and enhance the quality of the analysis. Here's how AI contributed:

Code Generation: AI provided usable code snippets for data exploration, visualization, and machine learning tasks, significantly speeding up implementation.

Troubleshooting: It helped debug issues like correctly labeling and formatting plots and ensuring proper metric evaluation.

Concept Clarification: For metrics like precision, recall, and F1-score, AI provided explanations and examples that were commented into the notebook.

Time Efficiency: Tasks that would have taken hours to research and implement manually were completed in minutes with AI.



   Using AI for this assignment had many benefits. One benefit was that it sped up the process. Instead of having to type everything out, it typed everything for me much faster than I could. There were many repetitve processes and ChatGPT was fast at it. Also, if I had questions on why something wasn't working, it would help be trouble shoot. Every move was clear and laid out. Another benefit is that it didn't need to be reminded what certain topics were or how to calculate things like the model metrics. It already knew everything. 

   One danger could be if someone doesn't know why specific metrics are used, the results could be misinterpreted. Overfitting and underfitting could be a problem that might remain unchecked. A model might be suggested with high accuracy, but low recall for fraud detection, which would not be a good thing in this case. As for when I needed to correct the AI output, I needed to change some colors on the heatmap and bar graphs for example. Another one was when the legends for the scatterplots had the same color, I needed to change some code to correctly display the legend. 
