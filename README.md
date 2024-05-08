# Use-case-2: World Happiness Analysis

## Overview

This project focuses on analyzing global happiness data sourced from the Gallup World Poll, provided by Kaggle. The datasets explore various factors influencing happiness across countries, including economic production, social support, life expectancy, freedom, absence of corruption, and generosity. The analysis includes a detailed examination of data quality and profiling to ensure reliability and relevance for deriving insights.

## About the Dataset

- **Source**: Kaggle (Gallup World Poll)
- **Key Concepts**:
  - **Dystopia**: An imaginary country with the least happy populace, used as a benchmark.
  - **Utopia**: A hypothetical ideal counterpart to Dystopia.
  - **Dystopia Residual**: A factor in calculating the happiness score, representing elements unexplained by the report's metrics.

## Data Profiling and Quality Checks

### Reliability

- **Source**: Gallup World Poll via Kaggle
- **License**: CC0 - Public Domain, ensures unrestricted public use.
- **Data Timeliness**: The dataset is suitable for this analysis.

### Consistency

- Variation in error measurements across datasets (e.g., Standard Error, Whiskers, Confidence Intervals).
- Discrepancies in column naming conventions which could affect dataset merging, though no merging planned for this project (currently).
- The 2018 dataset lacks one value in the 'Perceptions of corruption' column, which was addressed by imputing missing values.

### Relevance

- Maintained various error measurement methods as they may be relevant for deeper analysis.

### Uniqueness

- Each dataset is unique.

### Completeness

- Addressed missing values through mean imputation for the 2018 dataset.
- Ensured completeness in the happiness score calculation by adding the missing 'Dystopia Residual' columns to the 2018 and 2019 datasets, aligning them across different years.

## Processed Tasks

1. **Data Loading (Day 1-2)**: Loaded the datasets for analysis.
2. **Data Quality Checks (Day 1-2)**: Conducted thorough quality checks to validate reliability, timeliness, consistency, relevance, uniqueness, and completeness. Checked accuracy.
3. **Data Clean (Day 2)**: Checked the data. but nothing to clean

## Setup Instructions

1. Download the datasets from [Kaggle's World Happiness Report page](https://www.kaggle.com/datasets/unsdsn/world-happiness/).
2. Ensure Python 3.x and necessary libraries (pandas, numpy) are installed.
   ```bash
   pip install pandas numpy
   ```

**_Riyadh Alghamdi_**
