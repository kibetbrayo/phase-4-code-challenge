# phase-4-code-challenge

This is a simple RESTful API for managing restaurants and their associated pizzas.

Before running the API, make sure you have the following installed:

- Python 3
- Flask
- Flask-RESTful
- Flask-SQLAlchemy
- SQLAlchemy
- Other project-specific dependencies (install using `pip`)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/kibetbrayo/phase-4-code-challenge.git
   cd restaurant-pizza-api

2. install the required dependancies
      pip install -r requirements.txt

3. setup the database migration
    flask db upgrade

4. run api
     flask run

## Usage

## Endpoints

Index

- GET '/'

- Description: Welcome message
- Response: Welcome message in JSON format
- Restaurants

## GET /restaurants

- Description: Get a list of all restaurants
- Response: List of restaurants in JSON format

## POST /restaurants

- Description: Create a new restaurant
- Request: JSON data with restaurant details
- Response: JSON representation of the created restaurant

Restaurant by ID

## GET /restaurants/<int:id>

- Description: Get details of a restaurant by its ID
- Response: JSON representation of the restaurant

## PATCH /restaurants/<int:id>

- Description: Update details of a restaurant
- Request: JSON data with updated restaurant details
- Response: JSON representation of the updated restaurant

## DELETE /restaurants/<int:id>

- Description: Delete a restaurant by its ID
- Response: No content (204) if successful

Pizzas

## GET /pizzas

- Description: Get a list of all pizzas
- Response: List of pizzas in JSON format
Restaurant Pizzas

## GET /restaurant_pizzas

- Description: Get a list of all restaurant-pizza relationships
- Response: List of restaurant-pizza relationships in JSON format

## POST /restaurant_pizzas

- Description: Create a new restaurant-pizza relationship
- Request: JSON data with relationship details
Response: JSON representation of the created relationship

### Contributing

Contributions are welcome! Please fork the repository and create a pull request for any improvements or bug fixes
