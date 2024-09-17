# Basket-Wizard

This project implements Market Basket Analysis using Python and the Apriori algorithm. It analyzes transaction data from an online retail dataset to discover associations between products purchased together.Market Basket Analysis is a data mining technique used by retailers to understand purchasing patterns of customers. This implementation uses the Apriori algorithm to find frequent itemsets and generate association rules.

## Features

- Data cleaning and preparation
- Apriori algorithm implementation using mlxtend
- Association rule generation
- Filtering rules based on lift and confidence

## Key Functions

- my_encode_units(x): Encodes quantities into binary values (0 or 1)
- apriori(): Generates frequent itemsets
- association_rules(): Generates association rules

## Tech stack used
- **Python**: The primary programming language used for the implementation.
- **pandas**: Used for data manipulation and analysis.
- **numpy**: Supports large, multi-dimensional arrays and matrices, along with a collection of mathematical functions.
- **mlxtend**: Provides the implementation of the Apriori algorithm and association rules generation.

## Output

The script generates a set of association rules with metrics such as support, confidence, and lift. These rules can be used to make product recommendations or optimize store layouts.
