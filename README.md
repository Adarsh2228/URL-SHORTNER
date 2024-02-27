# URL Shortener

## Overview

This is a URL shortener project implemented using Node.js, Express.js, and MongoDB. The application takes a long website URL as input and returns a shortened URL. It also includes additional features such as timestamped visit history and tracking the number of clicks for a particular shortened URL.

## Features

1. **URL Shortening**: Enter a long website URL, and the application generates a short URL for easy sharing.
2. **Timestamped Visit History**: Keep track of the timestamped history of visits for each shortened URL.
3. **Click Count**: Monitor the number of clicks for each shortened URL to gauge its popularity.

## Technologies Used

- **Node.js**: A JavaScript runtime for server-side development.
- **Express.js**: A web application framework for Node.js, making it easier to handle routing and middleware.
- **MongoDB**: A NoSQL database used to store and retrieve URL data efficiently.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Adarsh2228/url-shortener.git
   ```

2. Install dependencies:

   ```bash
   cd url-shortener
   npm install
   ```

3. Set up MongoDB:

   - Install MongoDB on your machine.
   - Create a database and update the configuration in `config.js` or use a MongoDB URI.

4. Start the application:

   ```bash
   npm start
   ```

   The application will be running at `http://localhost:8001`.

## Usage

1. Access the application in your web browser.
2. Enter a long URL and click on the "Shorten" button.
3. Copy and share the generated short URL.
4. View visit history and click count for each shortened URL.

## Contributing

Feel free to contribute to the project by opening issues or creating pull requests. Your feedback and suggestions are highly appreciated.



---

Feel free to customize the sections according to your project structure and specifics. Make sure to update the URLs, placeholders, and any other details accordingly.
