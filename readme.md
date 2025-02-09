# JSON Server Setup

This project contains a `db.json` file with sample data for a cinema website. The JSON server provides a REST API endpoint to access this data.

## Prerequisites

-   [Node.js](https://nodejs.org/) (v12 or higher)
-   npm

## Installation

1. Install the project dependencies:

    ```bash
    npm install

    ```

2. Start the JSON server:

    ```bash
    npx json-server db.json

    ```

3. The server is now running at http://localhost:3000.

Available Endpoints

The following endpoints are available:
• /featured_movies
• /movies
• /cinemas
• /reviews
• /news
• /config
• /staff

Use these endpoints to retrieve data for your application.

Happy coding!
