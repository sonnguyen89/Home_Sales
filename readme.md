Crypto Clustering Challenge Repository

This repository contains a Jupyter Lab script for SparkSQL to determine key metrics about home sales data. 
This Jupyter notebook script uses Spark to create temporary views, partition the data, cache and uncache a temporary table,
and verify that the table has been uncached

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

this Jupyter Lab will analyse the Home Sales Data and answers following 4 questions:

    -   What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    -   What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    -   What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    -   What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

## Usage

Open the Jupyter Lab and open the repository "Home_Sales.ipynb" 


## Scripts

Jupiter Note scripts available in this repository:

- `Home_Sales.ipynb`: A script to read the csv files from AWS storage,  and export it to the Spark SQL.


Feel free to explore and modify these scripts to suit your specific needs.

## Contributing

Contributions to this repository is not welcome since this is just a homework


## License

This repository is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions, suggestions, or concerns regarding this repository, please don't hesitate to contact the repository owner:

- Email: [nam_son14@yahoo.com](mailto:nam_son14@yahoo.com)
- GitHub: [sonnguyen89](https://github.com/sonnguyen89)