
# Bored Activity Finder

## This project is a simple web application that consumes the [Bored API](https://bored-api.appbrewery.com/) to provide users with an activity based on the type and number of participants. The application is built using Node.js with Express, Axios for API consumption, EJS for templating, and body-parser for parsing form data.

## Installation

1. Clone the repository
   ```bash
   git clone git@github.com:Nickgalant/bored-activity-finder.git

2. Install dependencies
   ```bash
   npm install

3. Start the application
   ```bash
   npm start

## Usage
1. Open your browser and navigate to
   ```bash
   http://localhost:3000

2. Fill out the form
 * Select the type of activity from the dropdown menu.
 * Select the number of participants.

3. Submit the form
 * Click the "Go" button to fetch an activity based on your input.

4. View the result
 * The resulting activity will be displayed on the page.

## Project Structure
The project structure is as follows:
 * `index.js`: Main Express application file.
 * `public/`: Directory containing static files (CSS).
 * `views/`: Directory containing EJS templates.

## APIs Used
 * Bored API: An API that provides a random activity to help you fight boredom. More info at https://www.boredapi.com/.

## Dependencies
 * Express.js: Fast, unopinionated, minimalist web framework for Node.js.
 * EJS: Embedded JavaScript templates for rendering dynamic content.
 * body-parser: Node.js body parsing middleware, required for handling POST requests.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.