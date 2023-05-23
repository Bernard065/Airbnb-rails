# Airbnb-rails
The project aims to replicate some of the core features of the Airbnb platform. It likely includes functionality for user authentication, database management, front-end development using Turbo Streams, Stimulus, and Tailwind CSS, as well as geolocation capabilities using the Geocoder gem.

## Instructions to Run the Project

1. Prerequisites:
    .Ensure that Ruby version 2.7.4 is installed on your system.
    .Make sure you have PostgreSQL installed and running as the project uses the pg gem for database management.

2. Clone the Repository:

    .Clone the project's repository to your local machine using Git.

3. Install Dependencies:

    .Open a terminal or command prompt and navigate to the project's directory.

    .Run the following command to install the required gems specified in the Gemfile:
    `bundle install`

4. Set Up the Database:

    .Run the following commands to create the database, run migrations, and seed the database (if there are any seed data provided):

    ```javascript
    rails db:create
    rails db:migrate
    rails db:seed
    ```
5. Start the Rails Server:

    . Run the following command to start the Rails server:
    `rails server`
