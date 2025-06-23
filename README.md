# Chocolate Bar Ratings Analysis

This project explores the **Chocolate Bar Ratings dataset** from Kaggle, containing 1,795 reviews of 440 unique bars between 2006–2017. Reviews were submitted by chocolate enthusiasts and include sensory scores and metadata like cocoa content, origin, and manufacturer.

## 📁 Project Structure

* `data/`: Raw and cleaned dataset
* `scripts/`: Notebooks and Python scripts for analysis
* `visualizations/`: Charts and graphics generated from the data

## 📊 Dataset Overview

**Source**: Kaggle
**Years**: 2006–2017
**Entries**: 1,795
**Unique Bars**: 440

### Key Columns

* `Company`: Manufacturer name (416 unique)
* `BarName`: Bean origin or bar variant (1,039 unique)
* `CocoaPercent`: Cocoa content (%)
* `Rating`: Sensory rating (1.0–5.0 scale)
* `ReviewDate`: Year of review
* `BeanType`: Cacao variety (50% missing)
* `BroadOrigin`: Bean origin country (100 unique)
* `Location`: Company’s country (60 unique)

### Data Limitations

* No reviews after 2017
* Reviewer base skews toward enthusiasts
* 50% missing `BeanType`
* Licensed for educational use only

## 🧠 Motivation

I chose this dataset due to my interest in **specialty foods** and **flavor profiling**. Its diversity in geography and chocolate formulation allows for rich spatial and statistical analysis.

## ❓ Key Questions

* Does cocoa percentage affect rating?
* What rating trends exist from 2006–2017?
* Which origins yield the highest-rated chocolate?
* Are ratings influenced by company location?
* Can ratings be predicted from ingredients and origin?
* Are preferences shifting toward darker chocolate?

## 🛠️ Cleaning Summary

* Standardized column names
* Converted `CocoaPercent` to float
* Converted date and ratings to numeric
* Replaced missing `BeanType` with `"Unknown"`
* Retained 1 missing `BroadOrigin` for transparency
* No duplicates; all values validated

## ⚖️ Ethics

* Attribution required
* No personal data included
* Dataset may overrepresent niche chocolate bars

