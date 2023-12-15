# Meal Plan Generator

## Overview

The Meal Plan Generator is a web application that helps users create personalized meal plans based on their age, weight, height, gender, activity level, and dietary preferences. It utilizes the Edamam API to fetch recipe data that aligns with the user's requirements.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- User input form for age, weight, height, gender, activity level, number of meals, diet preference, and health specifications.
- Calculates the Basal Metabolic Rate (BMR) based on user information.
- Sends requests to the Edamam API to retrieve recipe data.
- Displays a weekly meal plan with recipe names, images, and links to view the full recipe.

![Meal Plan Generator](/plan.png)
![Generated Plan](/gen-plan.png)

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/meal-plan-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd meal-plan-generator
   ```

3. Open `index.html` in a web browser or set up a local server to run the application.

## Usage

1. Open `index.html` in a web browser.
2. Fill out the form with your personal information and preferences.
3. Click the "Generate Meal Plan" button.
4. View the generated meal plan, which includes recipes for each day of the week.

## Dependencies

- [Edamam API](https://developer.edamam.com/edamam-recipe-api)
- Internet connection to fetch recipe data from the Edamam API.

## Contributing

If you would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make changes and commit them.
4. Push the changes to your fork.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this README to better fit your project structure and details.
