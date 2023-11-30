# Restaurant Recommendation System

This Python program recommends restaurants based on the user's choice of cuisine.

## Features

- Accepts user input for the type of food.
- Recommends a restaurant serving the selected cuisine with the highest rating and closest proximity.
- Handles invalid inputs gracefully by providing no recommendations.

## How to Run the Program

1. Ensure you have Python installed on your system.
2. Download the restaurant_recommendation.py file from the GitHub repository.
3. Run the program in a terminal or command prompt with python restaurant_recommendation.py.
4. When prompted, enter the type of cuisine you are interested in.
5. The program will output a recommendation if available.

## How to Use the recommend_restaurant Function

- The function is defined as recommend_restaurant(food_type).
- Pass the desired cuisine type as a string to the function.
- The function returns a sorted list of recommendations based on rating and proximity.

## Example

```python
recommendations = recommend_restaurant("Italian")
print(recommendations)
