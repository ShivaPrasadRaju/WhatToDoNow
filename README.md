# Bored API Activity Suggester

This is a simple web application that suggests activities to do when you're bored. It uses the [Bored API](https://bored-api.appbrewery.com/) to fetch activities.

## Features

- Get a random activity suggestion.
- Filter activities by type and number of participants.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repository
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the server:
   ```bash
   npm start
   ```
2. Open your browser and go to `http://localhost:3000`.

## Dependencies

- [axios](https://www.npmjs.com/package/axios): For making HTTP requests to the Bored API.
- [body-parser](https://www.npmjs.com/package/body-parser): For parsing incoming request bodies.
- [ejs](https://www.npmjs.com/package/ejs): As the template engine.
- [express](https://www.npmjs.com/package/express): As the web framework.
