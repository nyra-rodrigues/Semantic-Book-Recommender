# Semantic Book Recommender

A sophisticated book recommendation system that uses semantic analysis to provide personalized book suggestions based on user preferences and book descriptions.

## Overview

This project implements a semantic book recommendation system that analyzes book descriptions, categories, and metadata to provide intelligent book suggestions. It uses natural language processing and semantic analysis to understand the content and context of books, going beyond simple keyword matching to provide more meaningful recommendations.

## Features

- Semantic analysis of book descriptions
- Comprehensive book metadata processing
- Personalized recommendation system
- Support for multiple book categories
- Integration with book metadata from various sources

## Dataset

The project uses a dataset containing over 7,000 books with rich metadata including:
- Book titles and subtitles
- Author information
- Categories and genres
- Book descriptions
- Publication years
- Average ratings
- Number of pages
- Rating counts

## Project Structure

- `book-recommender.ipynb`: Main Jupyter notebook containing the recommendation system implementation
- `books_cleaned.csv`: Processed and cleaned book dataset
- `tagged_description.txt`: Processed book descriptions with semantic tags
- `.env`: Environment configuration file

## Requirements

The project requires Python and the following key dependencies:
- pandas
- numpy
- scikit-learn
- nltk
- kagglehub
