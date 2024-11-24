# Frequency Analysis of Values

This project contains a script that performs a frequency analysis on a set of numerical values. It calculates the following statistics:

- Sorted values
- Range of the values
- Frequency distribution using intervals (class intervals)
- Absolute frequency
- Relative frequency
- Cumulative frequency
- Class midpoint

The goal of this script is to help visualize the distribution of the data and is useful in statistical analysis.

## Features

- **Sort Values**: Sorts the input values in ascending order.
- **Range Calculation**: Calculates the range of the values and adjusts it to the next multiple of the number of classes.
- **Interval Creation**: Divides the range into equal intervals (classes).
- **Absolute Frequency Calculation**: Computes how many values fall into each interval.
- **Relative Frequency Calculation**: Computes the relative frequency of each class.
- **Cumulative Frequency Calculation**: Computes the cumulative frequency up to each class.
- **Class Midpoint Calculation**: Calculates the midpoint of each class interval.

## Usage

1. Clone the repository or download the script.
2. Ensure that the `VALUES` array is populated with the dataset you want to analyze.
3. Run the script.

### Example Data:

```javascript
const VALUES = [
  160, 168, 174, 169, 180, 165, 173, 174, 170, 168, 172, 164, 164, 170, 167,
  178, 175, 165, 176, 165, 161, 170, 172, 179, 160, 177, 174, 167, 162, 171,
  177, 167, 163, 177, 165, 178, 170, 170, 174, 165, 166, 170, 170, 168, 178,
  166, 175, 176, 168, 167,
];
