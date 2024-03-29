# Frequent Itemset Generation and Association Rule Mining

This project focuses on generating frequent itemsets and mining association rules from transaction data of various retailers. The project implements three different methods for frequent itemset generation: brute force, Apriori, and FP-Growth. It also compares the performance of these methods.

## Project Overview

The project consists of two main parts:

1. **Data Preparation and Pattern Generation**: In this part, items for each retailer are defined, and deterministic transactions are generated based on certain patterns. These patterns are designed to reflect the unique characteristics of each retailer.

2. **Frequent Itemset Generation and Association Rule Mining**: This part involves loading the transactions, generating frequent itemsets using the three methods (brute force, Apriori, and FP-Growth), and mining association rules from the frequent itemsets. The performance of the three methods is compared in terms of execution time.

## Dependencies

The project requires the following dependencies:

- pandas
- mlxtend
- pyfpgrowth

You can install the dependencies using pip:

pip install pandas mlxtend pyfpgrowth

## Usage

1. Clone this repository: git clone https://github.com/your-username/your-repository.git
2. Navigate to the project directory: cd your-repository
3. Run the Jupyter Notebook: jupyter notebook Transaction_Mining_notebook.ipynb
4. Follow the instructions in the notebook to execute the code cells.

## Dataset

The project uses deterministic transactions generated based on predefined patterns for each retailer. The patterns are designed to reflect the unique characteristics of each retailer, such as Amazon, Wayfair, Walmart, Best Buy, and Nike.

## Methods

The project implements three methods for frequent itemset generation:

1. **Brute Force**: This method generates all possible itemsets and checks their support against the minimum support threshold.

2. **Apriori**: This method uses the Apriori algorithm to generate frequent itemsets by iteratively pruning infrequent itemsets.

3. **FP-Growth**: This method uses the FP-Growth algorithm to generate frequent itemsets using a compressed data structure called the FP-tree.

Association rules are then generated from the frequent itemsets using the specified minimum confidence threshold.

## Results

The project provides the following results:

- Frequent itemsets generated by each method
- Association rules mined from the frequent itemsets
- Performance comparison of the three methods in terms of execution time

## Acknowledgments

This project was developed as part of the coursework at New Jersey Institute of Technology (NJIT).
