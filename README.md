# ENSF_233_Final_Project

This project provides a program that analyzes and compares various statistics for two countries in the United Nations (UN). The program uses data from CSV files for population, threatened species, and country information to calculate and display the requested statistics.

## Dependencies
- numpy: A library for numerical computing.
- matplotlib: A library for creating visualizations.

## Class: printCountryInfo
- `country_name`: String representing the country's name.
- `UN_region`: String representing the UN region the country is in.
- `area`: String representing the country's size in square kilometers.
- `pop_ave`: Integer representing the calculated average population over the given range of years.
- `total_threatened`: Integer representing the calculated total amount of threatened species over the given range of years.

### Method: print_stats()
Prints selected statistics for the inputted country.

## Function: average_pop(country_index, population_data)
Calculates and returns the average population across the given range of years for the inputted country.

- `country_index`: Integer representing the index of the given country.
- `population_data`: Array representing data read in from a CSV file (population data from 2000-2020 for all UN countries).

## Function: total_threatened(country_index, threatened_data)
Calculates and returns the total amount of threatened species for the inputted country.

- `country_index`: Integer representing the index of the given country.
- `threatened_data`: Array representing data read in from a CSV file (threatened species data for all UN countries).

## Function: pop_density(country_index, population_data, country_size)
Calculates and returns a list of all the population densities for the inputted country over the given range of years.

- `country_index`: Integer representing the index of the given country.
- `population_data`: Array representing data read in from a CSV file (population data from 2000-2020 for all UN countries).
- `country_size`: Integer representing the size of the country in square kilometers.

## Function: main()
The main function of the program that executes the analysis and visualization steps.

- Reads CSV files for country data, population data, and threatened species data.
- Prompts the user to input two valid countries from the UN.
- Calculates average population, total threatened species, and population density for the selected countries.
- Prints statistics for each country.
- Displays visualizations comparing population, threatened species, and population density for the selected countries.

Note: The code assumes the availability of CSV files named 'Country_Data.csv', 'Population_Data.csv', and 'Threatened_Species.csv' for reading data.

## Authors
Oluwafisayo Adabs - @fisayoadabs
Kameel Kasumu - @kameelkas
