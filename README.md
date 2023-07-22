# Pizza API

This repository contains A Mock Pizza API, a simple JSON-based API to retrieve information about various delicious pizzas from different restaurants. It provides endpoints to access pizza data, such as names, descriptions, ingredients, and restaurant information.

## API Endpoints

1. `GET /pizzas`: Retrieves a list of all available pizzas along with their details.

2. `GET /pizzas/:id`: Retrieves the details of a specific pizza based on its ID.

## Database (db.json)

The `db.json` file contains the data for the pizzas served by different restaurants. Each pizza object includes the following information:

- `id`: Unique identifier for the pizza.
- `name`: The name of the pizza.
- `restaurant`: The name of the restaurant that serves the pizza.
- `web`: The website URL of the restaurant.
- `description`: A brief description of the pizza's taste and toppings.
- `ingredients`: An array of ingredients used to make the pizza.
- `address`: The address details of the restaurant, including address ID, street number, street lines, postcode, and country.

