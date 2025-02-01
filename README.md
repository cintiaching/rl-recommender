# rl-recommender
A product recommender that use reinforcement learning.

## Overview
The RL-Recommender is a product recommendation system that utilizes reinforcement learning techniques to enhance the shopping experience for products that require user trials. This system aims to identify the most suitable products in the shortest possible time, thereby expediting the purchasing process.

## Concept
The core idea is to present users with a variety of products, allowing them to try these products and subsequently provide ratings based on their experiences. This feedback loop enables the system to learn and adapt, ultimately showcasing better-suited products to the user over time.

### Example Products
The system is particularly beneficial for products such as:
- Fragrance and Beauty products
- Candles and essential oils
- Tea or Coffee Blends
- Craft Beers or Wines

## Data
- User reviews of the products -> for training and validation
- Product attributes -> for training, to help personalize recommendations

## Process
1. **Product Presentation**: Randomly selected products are displayed to the user.
2. **User Interaction**: Users try the products and provide ratings based on their experiences.
3. **Learning and Adaptation**: The system analyzes the ratings to refine its recommendations, ensuring that better products are presented in future interactions.

