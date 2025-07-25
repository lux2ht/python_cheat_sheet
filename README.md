

# UK Referendum Data Analysis Project

This project provides tools and code for analyzing the UK Referendum datasets using Python, without relying on pandas. It is designed for educational purposes and demonstrates data loading, transformation, and analysis using only built-in Python libraries and the `requests` package.

## Project Overview

The project includes:

- Downloading and loading JSON datasets from public URLs using Python's `requests` library
- Merging and manipulating data structures (lists and dictionaries)
- Calculating summary statistics (max, min, median, quartiles)
- Sorting and filtering data
- Performing region-wise aggregations
- Example functions for common data operations

## Files

- `script_no_pkg.ipynb`: Jupyter Notebook with python native classes.
- `script_pands.ipynb`: Jupyter Notebook with panda dataframe.
- `README.md`: Project documentation and instructions.
- `LICENSE`: MIT License for open source use.

## Data Sources

- [UK Demographic Data](https://raw.githubusercontent.com/viveknest/statascratch-solutions/main/UK%20Referendum%20Data/uk_demo.json)
- [UK Referendum Results](https://raw.githubusercontent.com/viveknest/statascratch-solutions/main/UK%20Referendum%20Data/uk_results.json)
- [UK Rejected Ballots](https://github.com/viveknest/statascratch-solutions/raw/main/UK%20Referendum%20Data/uk_rejected_ballots.json)

## Requirements

- Python 3.x
- Jupyter Notebook
- `requests` library (install with `pip install requests`)
- `pandas` library (install with `pip install pandas`)

## Usage

1. Open `script_no_pkg.ipynb` or `script_pands.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to reproduce the analysis and view outputs.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or new features.

## License

This project is open source and licensed under the MIT License. See the LICENSE file for details.
