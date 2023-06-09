# Project Title: Améliorez le produit IA de votre start-up

This project aims to enhance the AI product of the startup "Avis Restau" by introducing a new collaboration feature. The goal is to allow users to post reviews and photos of their favorite restaurants while enabling the company to gain better insights into user-generated reviews.

## Use Case

As a user of Avis Restau, I can:
- Post reviews in the form of comments.
- Upload photos taken at the restaurant.

As Avis Restau, we want to:
- Detect dissatisfaction topics from the comments posted on the platform.
- Automatically label the photos posted on the platform, such as identifying food-related photos, restaurant decor, or exterior views.

## Project Scope

The project scope includes:
- Preliminary study of the "Detect dissatisfaction topics" and "Automatically label posted photos" features.
- Dataset exploration and selection.

## Dataset

Problem: Insufficient data on the Avis Restau platform.
Solution: Utilize an existing dataset.
Dataset Link: [Yelp Dataset](https://www.yelp.com/dataset)
The dataset contains general information (e.g., cuisine type) and consumer reviews for different restaurants.
Due to the dataset's volume, refer to [this article](https://example.com) for instructions on how to load it completely.

## Data Collection

Problem: Ensure the possibility of collecting new data.
Solution: Collect new data using the Yelp API. Validate the feasibility by collecting information about approximately 200 restaurants for a specific city using the API.
API Documentation: [Yelp API Documentation](https://example.com)

## Tools

- Python and specialized NLP/CV libraries.
- Jupyter Notebook and Voilà package.
