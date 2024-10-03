## Project Overview

This project analyzes the supply chain of ingredients for making avocado toast in the UK using data manipulation and analysis techniques. The objective is to determine the most common country of origin for each of the three key ingredients: avocados, olive oil, and sourdough bread.

In this project, I worked with a food dataset containing detailed information about product origins and associated characteristics. The focus was to subset relevant columns from the dataset, clean and manipulate the data, and identify the top countries of origin for the three main ingredients.

### Key Questions

- What is the most common country of origin for avocados?
- What is the most common country of origin for olive oil?
- What is the most common country of origin for sourdough bread?

These results are stored in the following variables:
- `top_avocado_origin`
- `top_olive_oil_origin`
- `top_sourdough_origin`

### Data Processing

The dataset was filtered to focus on these columns:
- `code`
- `lc`
- `productnameen`
- `quantity`
- `servingsize`
- `packagingtags`
- `brands`
- `brandstags`
- `categoriestags`
- `labelstags`
- `countries`
- `countriestags`
- `origins`
- `origins_tags`

String cleaning was performed to ensure that country names contain only letters (A-Z) and spaces, removing any hyphens or other characters.

### Tools and Technologies Used

- **Python**: For data manipulation and analysis.
- **Pandas**: Used for data cleaning, subsetting, and aggregation.

### Results

After analyzing the data, the most common country of origin for each ingredient is as follows:
- **Avocados**: `Peru`
- **Olive Oil**: `Greece`
- **Sourdough**: `United Kingdom`

Feel free to explore the code further and modify it to investigate other food products or supply chains!
