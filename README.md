# Nutrition Analysis and Recipe Finder

This project is an interactive application that allows users to look up nutritional values, find recipes, and optain cooking tips. For the features click [here](#key-features)

### Table of Contents
- [Requirements](#requirements)
- [Key Features](#key-features)
- [Usage](#usage)
- [Obtainable Information](#obtainable-information)
- [API Information](#api-information)
- [Credits](#credits)
- [License](#license)

## Requirements

To use this project, you need to install the required dependencies. Install them by running the following command:

```sh
pip install -r requirements.txt
```

### The project relies on the following libraries:

- requests: For interacting with the Edamam API.
- BeautifulSoup: For scraping cooking tips from websites.
- ipywidgets: For creating interactive widgets like dropdown menus and buttons.
- regex: For selecting the tips by number.
- IPython.display: To make the dropdown menu visiable for example.

## Api information

API Information
To use the [Edamam API](https://www.edamam.com/), you need to create an account at Edamam to obtain the API credentials. Add the keys to the following placeholders in your code:

- app_id = ''
- app_key = ''

## Key Features

- **Nutritional Analysis:** Search for the nutritional values of any ingredient.  
- **Find Recipes:** Discover recipes based on ingredient, dietary preferences, health preferences or meal type.  
- **Cooking Tips:** Get helpful advice to improve your cooking skills.  

## Usage

### To use the application, follow these steps:
1. Run the application using the **Run All** button.
2. Select the desired option from the dropdown menu.
3. Enter the required information in the input fields.
4. Click the **Submit** button to get the results.
5. To restart and try to obtain other data, use the **Restart** button and repeat these steps.

## Obtainable information

### Choose one of the following options to get information:
1. Search for Nutritional Information
2. Find Recipes
3. Discover Cooking Tips

#### 1. Search for Nutritional Information  
   Enter the name of an ingredient with its quantity for example; 1 apple - English names are required.

#### 2. Find Recipes  
   Search for recipes based on an ingredient or dietary preferences. You can also filter recipes by diet preferences, health preferences or by type of meal.

#### 3. Discover Cooking Tips  
   Access a collection of helpful cooking tips.

## Credits

- Developed by [Bo Rondaij](https://github.com/bmmrxx).  
- APIs Used: [Edamam](https://developer.edamam.com/).

## License

This project is licensed under the [MIT License](LICENSE).