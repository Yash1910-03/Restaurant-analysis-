Restaurant Data Analysis - Complete Project Report

📊 LEVEL 1: BASIC DATA ANALYSIS

Task 1: Data Exploration and Preprocessing
Analysis: Initial dataset exploration and cleaning
Results:

Dataset contains 9,551 restaurants with 21 features

Only 9 missing values in 'Cuisines' column (filled with 'Unknown')

Target variable distribution: Ratings range from 0.0 to 4.9, mean = 2.67

Class imbalance: Heavy skew towards lower ratings, many unrated restaurants (rating = 0)

Task 2: Descriptive Analysis
Analysis: Statistical analysis of numerical and categorical variables
Results:

Average Cost for two: Mean = 1,199, varies widely (std = 1,613)

Price Range: Most common is range 2 (mid-price)

Country Distribution: India (4,342), USA (4,340), UAE (866), Brazil (725)

Top Cuisines: North Indian (936), North Indian+Chinese (511), Chinese (354)

Top Cities: New Delhi (5,473), Gurgaon (1,118), Noida (1,080)

Task 3: Geospatial Analysis
Analysis: Geographic distribution and location-rating correlation
Results:

Restaurant clusters in major urban areas across countries

Strong geographic correlation with ratings

Highest average ratings: Philippines (4.46), Australia (4.05), Canada (3.99)

Lowest average ratings: India (1.65)

Heat maps show clear rating patterns by location

📈 LEVEL 2: ADVANCED ANALYSIS

Task 1: Table Booking and Online Delivery
Analysis: Service availability impact on ratings
Results:

Table Booking: Only 12.12% offer, but they have much higher ratings (4.17 vs 2.45)

Online Delivery: 25.87% offer, positive correlation with ratings

Price Range Impact: Higher-priced restaurants offer more online delivery

Price Range 1: 12.55% offer delivery

Price Range 4: 40.20% offer delivery

Task 2: Price Range Analysis
Analysis: Pricing strategy and rating relationships
Results:

Most Common Price Range: 2 (mid-range) - 3,556 restaurants

Rating-Price Correlation: Higher price ranges = higher ratings

Price Range 1: 1.98 average rating

Price Range 4: 3.92 average rating

Best Rating Color: 'Dark Green' represents highest quality (4.59 average)

Task 3: Feature Engineering
Analysis: Creating new predictive features
Results:

Created Binary Features: Has Table Booking, Has Online Delivery

Length Features: Name Length, Address Length, Cuisine Count

Total Features: Increased from 21 to 30 features

Feature Statistics:

Average name length: 17.7 characters

Average cuisine count: 1.5 per restaurant

🤖 LEVEL 3: PREDICTIVE MODELING

Task 1: Customer Preference Analysis
Analysis: Cuisine preferences and rating patterns
Results:

Highest Rated Cuisines: Italian (4.12), Cafe (4.03), European (3.99)

Most Popular Cuisines: North Indian (42,345 votes), Chinese (19,876 votes)

Key Insight: Cafe cuisine balances high ratings and popularity

Trade-off: Some popular cuisines have moderate ratings

Task 2: Data Visualization
Analysis: Comprehensive visual exploration
Results:

Rating Distribution: Right-skewed with concentration in 2.5-3.8 range

Cuisine Comparison: Italian and Cafe consistently high-rated

City Patterns: Significant rating variations across cities

Feature Correlations: Votes and Price Range strongly correlate with ratings

Task 3: Predictive Modeling
Analysis: Machine learning model performance comparison
Results:

Traditional Models:

Linear Regression: R² = 0.4148, RMSE = 1.1611

Decision Tree: R² = 0.7726, RMSE = 0.7237

Random Forest: R² = 0.8267, RMSE = 0.6318 (BEST)

Deep Learning Models:

Single Perceptron: R² = ~0.41, similar to Linear Regression

Two-Layer Perceptron: R² = ~0.65-0.75, better than single layer

Key Findings:

Best Model: Random Forest (82.67% variance explained)

Most Important Feature: Votes (51.3% importance)

Prediction Error: ±0.63 rating points with best model

Feature Importance Order: Votes > Price > Cost > Table Booking

🎯 KEY BUSINESS INSIGHTS
Strategic Recommendations:
Premium Positioning: Higher price ranges correlate with better ratings

Service Differentiation: Table booking significantly boosts ratings

Cuisine Strategy: Italian and Cafe concepts perform exceptionally well

Geographic Expansion: Target locations with demonstrated high-rating potential

Customer Engagement: Vote count is strongest rating predictor - encourage reviews

Performance Metrics:
Data Quality: Excellent (minimal missing values)

Model Performance: Very good (82.67% R² with Random Forest)

Feature Effectiveness: Strong predictive power in engineered features

Actionable Insights: Multiple clear business recommendations

Limitations & Future Work:
Class Imbalance: Many low-rated restaurants

Geographic Bias: Heavy concentration in Indian market

Temporal Factors: No time-series analysis

Advanced Models: Potential for improved deep learning architectures


