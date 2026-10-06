# 🎬 Movie Recommendation System

A **content-based movie recommendation system** built using Python, Pandas, NumPy, and Scikit-learn.

The project analyzes movie metadata such as **overview, genres, keywords, tagline, cast, and director** to identify movies with similar content.

Along with recommendations, the system also provides movie details, genre-based search, language filtering, release-year filtering, rating-based filtering, and simple natural-language style queries.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Project Objectives](#-project-objectives)
- [Key Features](#-key-features)
- [Machine Learning Approach](#-machine-learning-approach)
- [System Workflow](#-system-workflow)
- [Dataset](#-dataset)
- [Data Preprocessing](#-data-preprocessing)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Feature Engineering](#-feature-engineering)
- [Text Preprocessing](#-text-preprocessing)
- [TF-IDF Vectorization](#-tf-idf-vectorization)
- [Cosine Similarity](#-cosine-similarity)
- [Recommendation Engine](#-recommendation-engine)
- [Search and Filtering](#-search-and-filtering)
- [Natural-Language Query System](#-natural-language-query-system)
- [Example Queries](#-example-queries)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Running the Project](#-running-the-project)
- [Testing](#-testing)
- [Results](#-results)
- [Limitations](#-limitations)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

# 📖 Overview

Choosing a movie to watch can be difficult because modern movie databases contain thousands of titles.

A recommendation system can help users discover movies that are similar to something they already like.

This project implements a **Content-Based Movie Recommendation System**.

The system does not depend on other users' ratings or viewing histories. Instead, it analyzes the information associated with each movie.

For example, if a user searches for:

```text
movies like Inception