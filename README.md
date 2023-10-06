# News Classification Project Overview:

1) Task:
The project involves text classification, where the content of news articles serves as input. The goal is to determine the appropriate category for each input article from a set of predefined categories: 'sports', 'business', 'politics', 'health', 'tech', and 'entertainment'.

2) Model:
For this task, I used the Random Forest classifier model. While this choice yielded favorable results, considering other models and methods could lead to further enhancements.

3) Dataset:
The dataset utilized for this project is sourced from the 'train.csv' file given in the folder . The file contains two main columns: 'excerpt', which represents the content of the news articles, and 'category', indicating the respective category of each article. The input provided to the algorithm is a vectorized representation of the 'excerpt', while the output corresponds to the category ID.

4) Challenges Encountered:
A primary challenge encountered during the project was the selection of the most suitable algorithm. Before employing the Random Forest classifier, I experimented with two other algorithms. Ultimately, Random Forest given more accuracy and performance, so I selected it for this project.
