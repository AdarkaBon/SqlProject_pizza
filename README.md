# SqlProject_pizza
# Ben's Pizzeria Database Project

## Overview

Ben is launching a new pizzeria in his town, focusing on take-out and delivery services akin to Domino's. To streamline operations and enhance business performance, Ben needs a custom-built relational database that will manage essential information related to customer orders, stock levels, and staff management. This database will be instrumental in creating interactive dashboards to monitor and evaluate business performance.

## Project Brief

### Situation

Ben's new pizzeria requires a robust system to handle the complexities of take-out and delivery services. The database will be central to managing various aspects of the business, including:

- Customer orders
- Stock levels
- Staff management

By capturing and storing this information efficiently, Ben will be able to monitor the performance of his business through detailed, interactive dashboards.

### Task

The initial phase of the project focuses on designing and building an orders table for the database. This table will include columns for:

- Item name
- Item category
- Item size
- Item price
- Quantity
- Customer first name
- Customer last name
- Delivery address
- Additional relevant details

The task also involves normalizing the data, adding related tables, and defining relationships to ensure data efficiency and flexibility.

### Action

The project consists of creating and connecting several tables within the database. Each table is given a unique ID and connected via this key. The tables include:

- Customers
- Orders
- Addresses
- Items
- Recipes
- Ingredients
- Inventory
- Rotas
- Shifts
- Staff

After constructing these tables and defining their relationships, the database will be exported for use in MySQL. Additionally, the project encompasses creating a dashboard to utilize the database for performance monitoring and evaluation.

### Result

Upon completion, this project will furnish Ben with a comprehensive database that:

- Effectively handles customer orders
- Ensures optimal stock management
- Facilitates efficient staff management

The interactive dashboards derived from this database will enable Ben to:

- Monitor business performance
- Gain valuable insights for informed decision-making

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/pizzeria-database.git
    ```
2. Set up the MySQL database by importing the provided SQL files.
3. Configure the connection settings in your application.
4. Run the provided scripts to populate the database with initial data.
5. Access the interactive dashboard to start monitoring business performance.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure that your code adheres to the project's coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact [Ben's Pizzeria](mailto:ben@pizzeria.com).

---

By creating this database, we aim to help Ben's Pizzeria achieve operational excellence and provide exceptional service to its customers. Thank you for being part of this project!
