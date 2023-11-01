# Categorizing Trends in Science

#### Notebook: [here](https://github.com/bossikkokossik/Trends-in-Science-ML)

## Project Intro/Objective
The primary aim of this project is to determine current scientific trends, thereby aiding the company's strategic shift towards research and academic collaboration. Using a vast dataset containing numerous recent scientific articles, we'll generate a quantitative overview of modern science themes. By clustering these articles, we intend to gain insights into current trends and potential academic partnerships, while also reducing data dimensions to capture the dataset's essence without overwhelming detail.

### Methods Used
* Exploratory Data Analysis
* Text Preprocessing and Feature Engineering
* Unsupervised Machine Learning (Clustering)
* Dimensionality Reduction
* Data Visualization

### Python Libraries
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* nltk
* wordcloud

## Project Description
We leverage a large archive of scientific papers sourced from [Arxiv](https://www.kaggle.com/Cornell-University/arxiv), a repository of electronic preprints for computer science, mathematics, physics, and more. The dataset's sheer volume makes it challenging to discern trends manually. However, by preprocessing the text data and employing machine learning techniques, we aim to categorize prevalent themes in recent scientific works. 

Initial steps involve exploratory data analysis to understand the data structure, followed by intensive text preprocessing to make it suitable for machine learning libraries. Feature engineering might be employed to enhance the data, making it more informative and better suited for clustering algorithms.

Upon refining the data structure, we would use clustering methods to categorize similar articles and employ dimensionality reduction techniques to provide a holistic, yet simplified view of the dataset. Iterative enhancements will be made to improve the project's accuracy and insights.

## Getting Started

1. **Data Setup**:
    - Download the dataset from [here](https://www.kaggle.com/Cornell-University/arxiv).
    - Extract the dataset and place it in a known directory.

2. **Clone this Repository**:
    - Detailed instructions on cloning a repository can be found [here](https://help.github.com/articles/cloning-a-repository/).

3. **Run the Notebook**:
    - Load the dataset into the notebook.
    - Follow the instructions in the notebook to preprocess the data, perform clustering, and visualize the trends.

4. **Data Structure**:
    - The dataset contains various fields like `title`, `summary`, `authors`, `categories`, etc. The primary columns for our analysis will be `title` and `summary`.

## Tips and Considerations
* It's crucial to understand the dataset's structure and nuances before diving into preprocessing.
* The dataset's size might require optimizations, possibly using batch processing or other memory-efficient techniques.
* Consider the importance of each text feature in the dataset. For example, the `title` and `abstract` may provide more relevant information about the paper's content than the author's name.
* During clustering, assessing cluster quality can provide feedback for refining preprocessing or choosing better hyperparameters.
* Visualization can be critical for understanding and communicating results, but ensure they convey meaningful insights without overwhelming the viewer.