# Statistic_Project

This project provides is a program that allows users to compare statistics between two countries. It uses several Python libraries, including numpy and matplotlib.

The code defines a class called `printCountryInfo` that represents country information such as name, UN region, area, average population, and total threatened species. The class has a method called `print_stats` that prints the statistics for a country.

The program also includes several helper functions:
- `average_pop`: calculates and returns the average population for a given country using population data.
- `total_threatened`: calculates and returns the total number of threatened species for a given country using species data.
- `pop_density`: calculates and returns a list of population densities for a given country using population data and country size.

The `main` function is the entry point of the program. It reads data from CSV files (`Country_Data.csv`, `Population_Data.csv`, and `Threatened_Species.csv`) using numpy's `genfromtxt` function. It prompts the user to enter two valid countries and retrieves their respective statistics using the helper functions and the `printCountryInfo` class. It also plots graphs to compare population, threatened species, and population density between the two countries using matplotlib.

Overall, the code provides a user-friendly interface to compare statistics and visualize data for different countries.

## Authors
- Oluwafisayo Adabs - @fisayoadabs
- Kameel Kasumu - @kameelkas

## Date Completed
- December 2021
