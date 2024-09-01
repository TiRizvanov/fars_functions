## FARS Functions Package

### Overview

This project is a homework assignment for the Johns Hopkins University Coursera course, designed to provide a set of R functions for working with the US National Highway Traffic Safety Administration's Fatality Analysis Reporting System (FARS) data. The package includes functions for reading, summarizing, and visualizing FARS data, which contains information about fatal traffic accidents across the United States.

### Functions

- **`fars_read`**: Reads FARS data from a specified file. It returns a data frame containing the data from the file.
- **`make_filename`**: Generates the filename for a FARS dataset based on a given year.
- **`fars_read_years`**: Reads and processes FARS data for multiple years, returning a data frame with the month and year of each accident.
- **`fars_summarize_years`**: Summarizes the number of fatal accidents per month for a given list of years.
- **`fars_map_state`**: Maps the accidents for a specified state and year, visualizing them on a map of the United States.

### Installation

To use this package, ensure that you have the required dependencies installed in your R environment. The package imports several libraries, including `dplyr`, `readr`, `tidyr`, `maps`, and `graphics`.

### Usage

After installing the package, you can use the provided functions to read and analyze FARS data files. Make sure the relevant FARS data files are downloaded and placed in the working directory before running the functions.

### Testing

A simple test is provided to verify the functionality of the `make_filename` and `fars_read` functions. You can run the test using the `testthat` library.

### Vignette

An introductory vignette is included to demonstrate how to use the main functions in this package. It provides examples of summarizing accident data by year and mapping accidents by state.

### Author

This package was created as part of a Coursera course by Johns Hopkins University. The task was accomplished by Timur Rizvanov, who can be reached at 1812timurr@gmail.com
