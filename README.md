# Seattle Airbnb Analysis

This repository contains an analysis of the Seattle Airbnb dataset, exploring various factors that contribute to successful Airbnb listings in Seattle. The analysis follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, consisting of six key phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.

## Business Understanding
Opening an Airbnb listing in Seattle raises important business questions that need to be addressed to ensure success in the market. Some of the key business questions to consider are:

1. Pricing Strategy: What is the optimal pricing strategy to maximize occupancy rates and revenue while remaining competitive in the market?

2. Guest Satisfaction: Which amenities have the greatest impact on guest satisfaction and positive reviews? How can the listing be optimized to enhance the overall guest experience?

3. Neighborhood Competitiveness: How does the pricing of the listing compare to similar properties in the neighborhood? Is the listing competitively priced to attract potential guests?

4. Market Demand: What are the peak seasons and periods of high demand for Airbnb rentals in Seattle? How can the listing be adjusted to meet the varying demand throughout the year?

By addressing these business questions, hosts can make informed decisions to optimize their Airbnb listing, attract more guests, increase revenue, and achieve a competitive edge in the Seattle market.

## Data Understanding
The Seattle Airbnb dataset, obtained from publicly accessible sources like Inside Airbnb and Kaggle, provides valuable insights into the Seattle Airbnb market. It includes information about listings, pricing, availability, amenities, and neighborhood details.

## Data Preparation
The data is preprocessed and cleaned to ensure its suitability for analysis. Missing values and irrelevant columns are handled appropriately, and categorical variables are transformed as needed. Exploratory data analysis is performed to gain a deeper understanding of the dataset.

## Modeling
Two different modeling techniques, linear regression and XGBoost, are employed to predict listing prices. The models consider factors such as the number of bedrooms, bathrooms, room type, and additional amenities to determine their impact on the listing price.

## Evaluation
The models' performance is evaluated using metrics such as Mean Squared Error and R-squared score. The results indicate the features that have the most significant influence on the price prediction.

## Deployment
The insights gained from the analysis can guide individuals in opening their own Airbnb listings in Seattle. Recommendations include pricing the listings within the $100-$200 range, adjusting prices during the holiday season, providing essential amenities like Wi-Fi and a kitchen, and staying competitive within the neighborhood.

## Results and Insights

The analysis yielded several key insights for individuals interested in opening an Airbnb listing in Seattle:

- Pricing: The majority of listings fall within the $100-$200 range, with a median price of $150. This range appears to be attractive for potential guests.
- Availability: September to January is the busiest period, while availability remains relatively consistent from January to March. Adjusting prices accordingly during these periods is recommended.
- Amenities: Essential amenities such as Wi-Fi, heating, and a kitchen greatly impact guest satisfaction. Providing these amenities is crucial for attracting and retaining guests.
- Neighborhood Influence: Neighborhoods play a significant role in pricing. Listings in the heart of the city command higher prices compared to those in less central areas. Understanding the relative pricing in different neighborhoods is essential for setting competitive rates


## Repository Structure
- `data/`: Directory containing the Seattle Airbnb dataset.
- `notebooks/`: Jupyter notebooks containing the analysis code.
- `images/`: Folder containing visualizations and graphs generated during the analysis.
- `README.md`: Readme file providing an overview of the analysis and its findings.

## Libraries used

```
notebook>=6.5.4
pandas>=2.0.3
numpy>=1.25.0
matplotlib>=3.7.0
scikit-learn>=1.3.0
scipy>=1.5.0
seaborn==0.12.2
xgboost==1.7.6
```
Here's how you can install : 

1. Open a command prompt or terminal and clone this repository. 

2. Navigate to the directory containing the `pyproject.toml` file.

3. Run the following command:

   ```bash
   pip install -r pyproject.toml
   ```

The project can further be made to build using poetry. But I will do that in the next versions!


## Conclusion
This analysis serves as a comprehensive guide for individuals interested in opening an Airbnb listing in Seattle. By following the CRISP-DM process and leveraging the Seattle Airbnb dataset, users can gain valuable insights into pricing strategies, amenities, and market competition, leading to a successful and profitable Airbnb venture in Seattle.
Here is a link to https://medium.com/@skandaextra1/unveiling-seattles-airbnb-market-a-visual-guide-for-opening-your-own-listing-4a76b5b1757e the medium post related to this!
