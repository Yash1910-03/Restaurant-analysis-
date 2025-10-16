<!DOCTYPE html>
<html>
<head>
    <title>Restaurant Data Analysis Report</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; }
        .level { border: 2px solid #333; padding: 20px; margin: 20px 0; border-radius: 10px; }
        .task { background: #f5f5f5; padding: 15px; margin: 10px 0; border-radius: 5px; }
        h1 { color: #2c3e50; text-align: center; }
        h2 { color: #34495e; border-bottom: 2px solid #3498db; padding-bottom: 10px; }
        h3 { color: #16a085; }
        .insight { background: #e8f6f3; padding: 10px; border-left: 4px solid #1abc9c; margin: 10px 0; }
        .result { background: #eaf2f8; padding: 10px; border-left: 4px solid #3498db; margin: 10px 0; }
    </style>
</head>
<body>

<h1>🍽️ Restaurant Data Analysis - Complete Project Report</h1>

<div class="level">
    <h2>📊 LEVEL 1: BASIC DATA ANALYSIS</h2>
    
    <div class="task">
        <h3>Task 1: Data Exploration and Preprocessing</h3>
        <div class="result">
            <strong>Analysis:</strong> Initial dataset exploration and cleaning<br>
            <strong>Results:</strong><br>
            • Dataset contains <strong>9,551 restaurants</strong> with <strong>21 features</strong><br>
            • Only <strong>9 missing values</strong> in 'Cuisines' column<br>
            • <strong>Target variable distribution:</strong> Ratings range from 0.0 to 4.9, mean = 2.67<br>
            • <strong>Class imbalance:</strong> Heavy skew towards lower ratings
        </div>
    </div>

    <div class="task">
        <h3>Task 2: Descriptive Analysis</h3>
        <div class="result">
            <strong>Analysis:</strong> Statistical analysis of numerical and categorical variables<br>
            <strong>Results:</strong><br>
            • <strong>Average Cost for two:</strong> Mean = 1,199, varies widely<br>
            • <strong>Most Common Price Range:</strong> 2 (mid-price) - 3,556 restaurants<br>
            • <strong>Country Distribution:</strong> India (4,342), USA (4,340), UAE (866)<br>
            • <strong>Top Cuisines:</strong> North Indian (936), North Indian+Chinese (511)<br>
            • <strong>Top Cities:</strong> New Delhi (5,473), Gurgaon (1,118), Noida (1,080)
        </div>
    </div>

    <div class="task">
        <h3>Task 3: Geospatial Analysis</h3>
        <div class="result">
            <strong>Analysis:</strong> Geographic distribution and location-rating correlation<br>
            <strong>Results:</strong><br>
            • <strong>Restaurant clusters</strong> in major urban areas<br>
            • <strong>Strong geographic correlation</strong> with ratings<br>
            • <strong>Highest average ratings:</strong> Philippines (4.46), Australia (4.05)<br>
            • <strong>Lowest average ratings:</strong> India (1.65)<br>
            • Heat maps show clear <strong>rating patterns by location</strong>
        </div>
    </div>
</div>

<div class="level">
    <h2>📈 LEVEL 2: ADVANCED ANALYSIS</h2>
    
    <div class="task">
        <h3>Task 1: Table Booking and Online Delivery</h3>
        <div class="result">
            <strong>Analysis:</strong> Service availability impact on ratings<br>
            <strong>Results:</strong><br>
            • <strong>Table Booking:</strong> Only 12.12% offer, but they have <strong>much higher ratings</strong> (4.17 vs 2.45)<br>
            • <strong>Online Delivery:</strong> 25.87% offer, positive correlation with ratings<br>
            • <strong>Price Range Impact:</strong> Higher-priced restaurants offer more online delivery<br>
            &nbsp;&nbsp;Price Range 1: 12.55% offer delivery → Price Range 4: 40.20% offer delivery
        </div>
    </div>

    <div class="task">
        <h3>Task 2: Price Range Analysis</h3>
        <div class="result">
            <strong>Analysis:</strong> Pricing strategy and rating relationships<br>
            <strong>Results:</strong><br>
            • <strong>Most Common Price Range:</strong> 2 (mid-range) - 3,556 restaurants<br>
            • <strong>Rating-Price Correlation:</strong> Higher price ranges = higher ratings<br>
            &nbsp;&nbsp;Price Range 1: 1.98 avg rating → Price Range 4: 3.92 avg rating<br>
            • <strong>Best Rating Color:</strong> 'Dark Green' represents highest quality (4.59 average)
        </div>
    </div>

    <div class="task">
        <h3>Task 3: Feature Engineering</h3>
        <div class="result">
            <strong>Analysis:</strong> Creating new predictive features<br>
            <strong>Results:</strong><br>
            • <strong>Created Binary Features:</strong> Has Table Booking, Has Online Delivery<br>
            • <strong>Length Features:</strong> Name Length, Address Length, Cuisine Count<br>
            • <strong>Total Features:</strong> Increased from 21 to 30 features<br>
            • <strong>Feature Statistics:</strong> Average name length: 17.7 characters
        </div>
    </div>
</div>

<div class="level">
    <h2>🤖 LEVEL 3: PREDICTIVE MODELING</h2>
    
    <div class="task">
        <h3>Task 1: Customer Preference Analysis</h3>
        <div class="result">
            <strong>Analysis:</strong> Cuisine preferences and rating patterns<br>
            <strong>Results:</strong><br>
            • <strong>Highest Rated Cuisines:</strong> Italian (4.12), Cafe (4.03), European (3.99)<br>
            • <strong>Most Popular Cuisines:</strong> North Indian (42,345 votes), Chinese (19,876 votes)<br>
            • <strong>Key Insight:</strong> Cafe cuisine balances high ratings and popularity<br>
            • <strong>Trade-off:</strong> Some popular cuisines have moderate ratings
        </div>
    </div>

    <div class="task">
        <h3>Task 2: Data Visualization</h3>
        <div class="result">
            <strong>Analysis:</strong> Comprehensive visual exploration<br>
            <strong>Results:</strong><br>
            • <strong>Rating Distribution:</strong> Right-skewed with concentration in 2.5-3.8 range<br>
            • <strong>Cuisine Comparison:</strong> Italian and Cafe consistently high-rated<br>
            • <strong>City Patterns:</strong> Significant rating variations across cities<br>
            • <strong>Feature Correlations:</strong> Votes and Price Range strongly correlate with ratings
        </div>
    </div>

    <div class="task">
        <h3>Task 3: Predictive Modeling</h3>
        <div class="result">
            <strong>Analysis:</strong> Machine learning model performance comparison<br>
            <strong>Results:</strong><br>
            
            <strong>Traditional Models:</strong><br>
            • Linear Regression: R² = 0.4148, RMSE = 1.1611<br>
            • Decision Tree: R² = 0.7726, RMSE = 0.7237<br>
            • <strong>Random Forest: R² = 0.8267, RMSE = 0.6318 (BEST)</strong><br><br>
            
            <strong>Deep Learning Models:</strong><br>
            • Single Perceptron: R² = ~0.41, similar to Linear Regression<br>
            • Two-Layer Perceptron: R² = ~0.65-0.75, better than single layer<br><br>
            
            <strong>Key Findings:</strong><br>
            • <strong>Best Model:</strong> Random Forest (82.67% variance explained)<br>
            • <strong>Most Important Feature:</strong> Votes (51.3% importance)<br>
            • <strong>Prediction Error:</strong> ±0.63 rating points with best model
        </div>
    </div>
</div>

<div class="level">
    <h2>🎯 KEY BUSINESS INSIGHTS & RECOMMENDATIONS</h2>
    
    <div class="insight">
        <h3>Strategic Recommendations:</h3>
        • <strong>Premium Positioning:</strong> Higher price ranges correlate with better ratings<br>
        • <strong>Service Differentiation:</strong> Table booking significantly boosts ratings<br>
        • <strong>Cuisine Strategy:</strong> Italian and Cafe concepts perform exceptionally well<br>
        • <strong>Geographic Expansion:</strong> Target locations with high-rating potential<br>
        • <strong>Customer Engagement:</strong> Vote count is strongest rating predictor
    </div>
<div class="insight">
        <h3>Performance Metrics Summary:</h3>
        • <strong>Data Quality:</strong> Excellent (minimal missing values)<br>
        • <strong>Model Performance:</strong> Very good (82.67% R² with Random Forest)<br>
        • <strong>Feature Effectiveness:</strong> Strong predictive power<br>
        • <strong>Data Points:</strong> 9,551 restaurants across 8 countries<br>
        • <strong>Models Tested:</strong> 5 different algorithms
    </div>
</div>

</body>
</html>
