# E-commerce Product Recommendation System

This project is an e-commerce platform built using Flask, which provides product recommendations to users. The system uses TF-IDF vectorization and cosine similarity to suggest products based on their descriptions. Users can sign up, sign in, and explore trending products with dynamic prices and random images.

## FEATURES

1.Product Recommendations: Provides content-based recommendations using TF-IDF and cosine similarity based on product descriptions.  
2.User Interaction: Users can view trending products and dynamically see different images and prices for each product.  
3.Sign-up/Sign-in System: Basic user authentication with sign-up and sign-in functionality (without SQL database).  
4.Dynamic Product Display: Displays trending products with randomly assigned images and prices for a dynamic experience.  

## PROJECT STRUCTURE

### Flask Framework: 
Used for backend and routing.
### Pandas:
For handling CSV data files containing product details.
### scikit-learn:
Used for implementing TF-IDF vectorization and cosine similarity for product recommendations.

## How It Works

Homepage: Users can view trending products with dynamic images and prices.  
Recommendations: Users input a product name to get content-based product recommendations. The system finds the top N most similar products based on product tags.  
Sign Up/Sign In: Users can create an account or log in to personalize their experience.  

## INSTALLATION

Clone the repository:  
git clone https://github.com/your-repo/ecommerce-recommendation-system.git  
cd ecommerce-recommendation-system  
Install the required dependencies:  
Run the Flask application:  
python app.py  
Visit the application  

## Data Files

models/trending_products.csv: Contains data for the trending products displayed on the homepage.  
models/clean_data.csv: Contains product data used for generating content-based recommendations.  

## How to Use

On the homepage, view the trending products displayed with random prices and images.  
Navigate to the recommendations page, enter a product name, and specify the number of recommendations you'd like to receive.  
The system will display the recommended products along with their details such as name, brand, and rating.  

## DEPENDENCIES

Flask  
Pandas  
Scikit-learn  
Flask-Bootstrap  

## EXAMPLE



