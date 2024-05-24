# Roommate Compatibility Analysis

This repository contains code and data for analyzing and predicting roommate compatibility using a Cosine Similarity model. The project leverages various personal traits, habits, and preferences to assess compatibility between potential roommates.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Preprocessing](#preprocessing)
- [Modeling with Cosine Similarity](#modeling-with-cosine-similarity)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Project Overview

The aim of this project is to predict the compatibility of potential roommates by analyzing their personal traits, habits, and lifestyle preferences using a Cosine Similarity model. The analysis involves data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset includes various features related to personal traits, habits, lifestyle preferences, and compatibility scores. It is stored in an Excel file with columns for each feature and target variables.

## Features

The dataset includes the following features:

- **Personal Traits**: Creativity, Openness to Diverse Cultures, Artistic Interests, Reliability, Attention to Detail, Sociability, Energy Levels, Assertiveness, Compassion, Cooperation, Trust in Others, Altruism, Modesty, Stress Management, Anxiety Levels, Mood Swings
- **Lifestyle Preferences**: Smoking and Drinking Habits, Cultural Values
- **Composite Scores**: LifeStyle Compatibility Score, Interest Match Score, Communication Compatibility, Interaction Potential, Environmental Preference, Core Values Score, Social Engagement Score, Responsibility Score, Openness to Experience Score, Emotional Intelligence Score
- **Target Variables**: Score, Personal Traits and Habits Category, Lifestyle and Cultural Preferences Category

## Preprocessing

The preprocessing steps include:
- Imputation of missing values using the mean strategy.
- Standardization of numerical features.
- One-hot encoding of categorical features.
- Creation of composite scores by averaging related features.

## Modeling with Cosine Similarity

This project uses a Cosine Similarity model to assess compatibility. The steps include:
- Converting feature vectors into a suitable format.
- Calculating cosine similarity between pairs of vectors.
- Predicting compatibility based on similarity scores.

## Evaluation

The model's performance is evaluated using:
- Similarity Scores
- Accuracy of predictions based on predefined thresholds

## Results

The results section highlights the performance of the model in predicting roommate compatibility, including metrics such as similarity scores and accuracy.

## Usage

To use this project:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/roommate-compatibility-analysis.git
    cd roommate-compatibility-analysis
    ```

2. **Install the required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare your dataset**: Place your dataset in the specified path or update the path in the script.

4. **Run the main script**:
    ```bash
    python main.py
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## References

1. Open Psychometrics. (n.d.). IPIP Big-Five Factor Markers. Retrieved from https://openpsychometrics.org/tests/IPIP-BFFM/
2. International Personality Item Pool. (n.d.). New IPIP-50-item Scale. Retrieved from https://ipip.ori.org/new_ipip-50-item-scale.htm
3. International Personality Item Pool. (n.d.). New Scoring Instructions. Retrieved from https://ipip.ori.org/newScoringInstructions.htm
4. Bus Study Mate. (n.d.). Retrieved from https://www.bustudymate.in/
