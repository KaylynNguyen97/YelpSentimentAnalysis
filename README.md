# Yelp Sentiment Analysis Project

## Overview
This project aims to help local businesses on Yelp interpret large volumes of unstructured customer reviews through sentiment analysis. By leveraging machine learning and natural language processing (NLP), we provide actionable insights that can enhance customer satisfaction, improve products, and ultimately boost revenue.

## Business Problem
- **Challenge**: Local businesses on Yelp struggle to interpret extensive user-generated data.
- **Impact**: Without the right tools, businesses miss opportunities to improve customer retention, brand reputation, and revenue.

## Proposed Solution
### Objective
Enable local businesses to optimize their Yelp presence using sentiment analysis to improve customer retention and operational decisions.

### Key Features
- **Review Quality Optimization**: Identify keywords and tones that drive higher ratings.
- **Predictive Customer Targeting**: Segment and retarget high-likelihood users.
- **Geographic Expansion Insights**: Determine optimal locations for new business openings.

### Expected Outcomes
- Increase in star ratings by approximately 0.2–0.5 on average.
- Improved retention and re-engagement rates.
- 15–25% performance boost through strategic location placement.

## Data Science Approach
### Goal
Utilize machine learning and NLP to perform sentiment analysis and deliver actionable insights.

### Methodology
- **Data Source**: Yelp Open Dataset (review text, star ratings converted to sentiment labels).
- **Target**: Binary sentiment classification of customer reviews.
- **Techniques**:
  - Text vectorization using Bag of Words, TF-IDF, and n-Grams.
  - Algorithms: Logistic Regression, Support Vector Machine, Random Forest.
  - Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC.

### Process Model
1. **Business Understanding**: Assess Yelp’s role as a connector between users and local businesses.
2. **Data Understanding**: Explore review patterns and user behavior.
3. **Data Collection**: Gather review data with ratings.
4. **Data Preprocessing**: Cleanse and label sentiment (positive/negative).
5. **Feature Engineering**: Vectorize text using selected techniques.
6. **Modeling**: Train classifiers and tune with GridSearchCV.
7. **Evaluation**: Cross-validate model accuracy and business relevance.
8. **Deployment & Monitoring**: Set up real-time sentiment scoring.

## Sentiment Analysis Model
- **Top Performer**: n-Gram + Logistic Regression.
- **Performance Metrics**:
  - Accuracy: 94%
  - Precision: 94%
  - Recall: 94%
  - F1 Score: 94%
  - ROC AUC: 98%
- **Benefits**: Minimizes false negatives and keeps false positives low, ideal for early-stage sentiment monitoring.

## Implementation Timeline
- **Phase 1**: Data collection and initial model development (Months 1-2).
- **Phase 2**: Pilot testing with 50 coffee shops in the Bay Area (Month 3).
- **Phase 3**: Dashboard development and API integration (Months 5-6).
- **Phase 4**: Full deployment and monitoring system (Month 7).
- **Phase 5**: Iteration & testing with 50 other small businesses (Month 4).
- **Phase 6**: Expand to 1000+ businesses across multiple categories (Months 8-12).


## Acknowledgments
- Team: Katrin Maliatski, Kaylyn Nguyen, Mahnoor Shahid, Rimsa Shrestha, Jenna Woo, & Christina Zhu.
