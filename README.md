# Introduction:

#### This repository provides a simple Python script for validating credit card numbers using the Luhn algorithm. The Luhn algorithm is a checksum formula used by many credit card companies to detect errors in card numbers.

# Functionality:

#### The script performs the following steps:

#### Preprocessing: Removes hyphens and spaces from the card number.
#### Reversal: Reverses the order of the digits.
#### Odd Digits: Sums the values of odd-positioned digits.
#### Even Digits: Doubles the values of even-positioned digits. If the result is greater than 9, it is split into individual digits and added.
#### Checksum: Calculates the total sum of all digits.
#### Validation: If the total sum is a multiple of 10, the card number is considered valid.

# Usage:

#### Clone the repository
#### Run the script
#### Enter a credit card number.
#### The script will display "VALID!" or "INVALID!" based on the verification result.

# Contributing:

#### Pull requests and suggestions are welcome! Please follow the contribution guidelines provided in the repository.
