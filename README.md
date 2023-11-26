# PSI Average Price and More

This program, developed by the Forex Robot Easy Team, is designed to calculate the average price and break even level for professional traders. It imports the necessary libraries and includes two main functions: calculateAveragePrice and calculateBreakEvenLevel.

## Features

### 1. Calculate Average Price

The function `calculateAveragePrice` takes in a vector of prices as input and calculates the average price by summing up all the prices and dividing it by the number of prices. It returns the average price.

### 2. Calculate Break Even Level

The function `calculateBreakEvenLevel` takes in the current balance and manual profit/loss as input and calculates the break even level. It adds the manual profit/loss to the current balance and returns the break even level.

## Usage

1. Import the necessary libraries: iostream and vector.

```cpp
#include <iostream>
#include <vector>
```

2. Call the `calculateAveragePrice` function and provide a vector of prices as input. It will return the average price.

```cpp
std::vector<double> prices = {1.2, 1.4, 1.6, 1.8, 2.0};
double averagePrice = calculateAveragePrice(prices);
```

3. Provide the current balance and manual profit/loss as input to the `calculateBreakEvenLevel` function. It will return the break even level.

```cpp
double currentBalance = 10000.0;
double manualProfitLoss = 500.0;
double breakEvenLevel = calculateBreakEvenLevel(currentBalance, manualProfitLoss);
```

4. Display the calculated data using `std::cout`.

```cpp
std::cout << 'Average Price: ' << averagePrice << std::endl;
std::cout << 'Break Even Level: ' << breakEvenLevel << std::endl;
```

## Product Description

PSI Average Price and More is a powerful Forex software developed by the Forex Robot Easy Team. It provides professional traders with the ability to calculate the average price and break even level. 

This software is designed to streamline the trading process by automating calculations that are crucial for traders to make informed decisions. By accurately calculating the average price, traders can analyze market trends and make strategic trading moves. Additionally, the break even level calculation helps traders determine the point at which they will neither make a profit nor a loss.

With PSI Average Price and More, traders can save time and effort by relying on the software to perform complex calculations accurately and efficiently. This allows them to focus on other aspects of their trading strategy and make informed decisions based on reliable data.

Please note that Forex Robot Easy is not the official developer of this product. We are providing a sample code that demonstrates how this product can work as described. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-psi-average-price-and-more-a-powerful-forex-software-for-professional-traders/). To find the official developer of this product, we recommend using MQL5, a trusted platform for Forex software development.
