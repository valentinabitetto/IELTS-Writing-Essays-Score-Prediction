# IELTS-Writing-Essays-Score-Prediction

## Project Overview
This project was developed as part of our Text Mining and Natural Language Processing (NLP) exam, in collaboration with Ana Suarez and Andrea Lolli. When planning to work or study abroad, demonstrating language proficiency is often required, particularly in English-speaking countries, where passing an English language proficiency test is necessary. Our project aims to create a model that can automatically grade text submissions, specifically essays.

## The Necessity of Automated Essay Grading

Assessing student performance is a vital aspect of education. Traditionally, this has been done manually by teachers. However, as student-to-teacher ratios increase, this method becomes more complex, time-consuming, and less reliable.

While online examination systems have effectively addressed multiple-choice question grading, there is still a significant gap in the automated evaluation of essays and short answers. The need for a robust system to handle these types of assessments is more pressing than ever.

## Our Approach

Acknowledging these challenges, we, as students, embarked on developing a solution. Utilizing our expertise in natural language processing (NLP), we crafted a model informed by global research. Our objective was to improve essay grading by evaluating multiple facets, including relevance, structural organization, semantics, syntax, and grammar.

## Project Objectives

The primary objective of our project is to develop a model that can predict essay scores based on the CEFR grading system. To achieve this, we utilize a dataset consisting of text samples from IELTS writing examinations.

## Methodology

To meet our objective, we utilized Natural Language Processing (NLP) techniques for text preprocessing and feature extraction to enhance our dataset. This enriched dataset was then used to train a model consisting of two layers of Bidirectional GRUs followed by a standard neural network.

To evaluate our model's performance, we experimented with various types of embeddings, including those derived from our textual data, PPMI, TF-IDF, and GloVe. Additionally, we performed hyperparameter tuning and benchmarked our models against a state-of-the-art algorithm, BERT.

## Getting Started

To replicate our project, you will need the following dependencies:

- [Dataset Link](https://www.kaggle.com/datasets/mazlumi/ielts-writing-scored-essays-dataset)
- [GloVe Embedding](https://drive.google.com/drive/folders/12NuXjRZvx4lEq58CRrlGBXohKidRe5wX?usp=sharing)
