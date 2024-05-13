# Django Delights Inventory Tracker

The Django Delights Inventory Tracker is a web application built with Django that helps restaurant owners keep track of their inventory, menu items, and purchases.

## Features

- Manage ingredients inventory with name, quantity, unit, and unit price
- Create and manage menu items with title and price
- Define recipe requirements for each menu item, specifying the required ingredients and quantities
- Record customer purchases of menu items
- Generate reports for total revenue, total cost, and profit

## Prerequisites

- Python 3.x
- Django 3.x

## Installation

1. Clone the repository:

2. Create a virtual environment and activate it:

3. Install the required dependencies:

4. Apply the database migrations:

5. Create a superuser account:

6. Run the development server:

7. Access the application in your web browser at `http://localhost:8000`.

## Usage

1. Log in to the Django admin interface at `http://localhost:8000/admin` using the superuser account created during installation.

2. Navigate to the Django Delights Inventory Tracker application.

3. Use the provided interfaces to manage ingredients, menu items, recipe requirements, and record purchases.

4. Generate reports to view the total revenue, total cost, and profit.

## Sample Data

To populate the database with sample data, run the following command:
- python manage.py populate_data

This will create sample ingredients, menu items, recipe requirements, and purchases.

## Testing

To run the test queries and view the results, follow these steps:

1. Open the Django shell:
- python manage.py shell

2. Execute the test queries:
```python
exec(open('test_queries.py').read())

### Example Output: 

All ingredients:
- Bread (20.0 loaves)
- Cheese (10.0 kg)
...

All menu items:
- Cheese Sandwich ($5.99)
- Tomato Sandwich ($4.99)
...

Recipe requirements for each menu item:
Cheese Sandwich requirements:
- Bread (2.0 loaves)
- Cheese (0.1 kg)
...

All purchases:
- Turkey Sandwich (purchased on 2024-05-11 18:29:44.274536+00:00)
- Club Sandwich (purchased on 2024-05-11 18:29:44.276154+00:00)
...

Total revenue: $71.40
Total cost: $76.40
Profit: $-5.00

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


License
This project is licensed under the MIT License. See the LICENSE file for more information.


This README provides an overview of the project, installation instructions, usage guidelines, information about sample data and testing, and instructions for contributing and licensing.

Regarding the remaining steps for the project:

1. Implement user authentication and authorization:
   - Create user registration and login views
   - Restrict access to certain views and actions based on user roles (e.g., admin, staff)

2. Add pagination to the list views:
   - Limit the number of items displayed per page
   - Provide navigation links to move between pages

3. Implement search functionality:
   - Allow users to search for ingredients, menu items, or purchases based on specific criteria

4. Add data validation and error handling:
   - Validate user input in forms
   - Display appropriate error messages for invalid data
   - Handle edge cases and potential errors gracefully

5. Enhance the user interface:
   - Improve the visual design and layout of the application
   - Use CSS and JavaScript to create a more engaging and interactive user experience

6. Implement additional reporting features:
   - Generate reports based on specific date ranges or other criteria
   - Visualize data using charts or graphs

7. Add unit tests:
   - Write unit tests to ensure the correctness of critical functionality
   - Set up continuous integration to automatically run tests on each code change

8. Optimize performance:
   - Analyze and optimize database queries for better performance
   - Implement caching mechanisms to improve response times

9. Deploy the application:
   - Choose a hosting platform (e.g., Heroku, AWS)
   - Configure the production environment
   - Set up a production database and perform necessary migrations
   - Deploy the application to the chosen platform

10. Perform thorough testing:
    - Conduct manual testing to identify any bugs or issues
    - Perform user acceptance testing to ensure the application meets the requirements
    - Address any identified issues and make necessary fixes

Remember to continuously update the README, commit your changes to version control, and maintain a clean and organized codebase throughout the development process.

Let me know if you have any further questions or if you need assistance with any of the remaining steps!

