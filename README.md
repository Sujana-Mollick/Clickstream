# Clickstream Data Analysis Project

## Introduction

This project focuses on analyzing **clickstream data**, which captures user navigation patterns on a website. The dataset includes information about user sessions, such as the sequence of pages visited and the time spent on each page. The goal is to uncover frequent patterns, user behavior, and insights that can help improve website design and user experience.

## Project Overview

The project involves the following key steps:
1. **Data Loading and Exploration**: Load the dataset and perform initial exploration to understand its structure.
2. **Data Preprocessing**: Clean and transform the data for analysis, including calculating average session durations.
3. **Frequent Pattern Mining**: Use algorithms like **Apriori** and **FP-Growth** to identify frequently visited page sequences.
4. **Association Rule Mining**: Generate association rules to understand relationships between different pages.
5. **Visualization**: Create visualizations to analyze page visit frequencies and session durations.

## Datasets

The dataset used in this project is stored in a CSV file (`Data2.csv`). It contains the following columns:
- `session_id`: Unique identifier for each user session.
- `Sequence`: Comma-separated list of pages visited during the session.
- `SequenceDurations`: Comma-separated list of time durations (in seconds) spent on each page.

## Datasets Included

### California Housing Data

- **Description**: This dataset contains information about housing in California from the 1990 US Census. It is commonly used for regression analysis to explore relationships between housing prices and various factors such as income, population, and geographical location.
- **Source**: [Dataset Documentation](https://docs.google.com/document/d/e/2PACX-1vRhYtsvc5eOR2FWNCwaBiKL6suIOrxJig8LcSBbmCbyYsayia_DvPOOBlXZ4CAlQ5nlDD8kTaIDRwrN/pub)
- **Usage**: Suitable for regression tasks, such as predicting housing prices based on features like median income, housing age, and population.
- **File Format**: CSV
- **Data Fields**: `median_income`, `housing_median_age`, `total_rooms`, `total_bedrooms`, `population`, `households`, `latitude`, `longitude`

### MNIST Sample Data

- **Description**: A subset of the MNIST database, which consists of images of handwritten digits. This dataset is ideal for training and testing machine learning models, particularly for image recognition tasks.
- **Source**: [MNIST Database](http://yann.lecun.com/exdb/mnist/)
- **Usage**: Commonly used for classification tasks, especially for introducing neural networks and other machine learning models to image recognition.
- **File Format**: CSV
- **Data Fields**: `pixel_values`, `label` (digit represented by the image)

### Anscombe's Quartet

- **Description**: A collection of four datasets that have nearly identical simple statistical properties but appear very different when graphed. This dataset is used to demonstrate the importance of visualizing data and not relying solely on statistical summaries.
- **Source**: Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American Statistician. 27 (1): 17-21. [JSTOR 2682899](https://www.jstor.org/stable/2682899)
- **Usage**: Ideal for illustrating the need for data visualization in statistical analysis.
- **File Format**: JSON
- **Data Fields**: `dataset_1: x, y`; `dataset_2: x, y`; `dataset_3: x, y`; `dataset_4: x, y`

## Additional Information

- These datasets are provided as samples and may require further preprocessing depending on the specific use case.
- Ensure to cite the original sources when using these datasets in academic or published work.


## Usage

### Prerequisites

To run this project, you need the following Python libraries:
- `pandas`
- `mlxtend`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:
```bash
pip install pandas mlxtend matplotlib seaborn scikit-learn

