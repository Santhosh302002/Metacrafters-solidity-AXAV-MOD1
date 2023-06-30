# CalculationExample

CalculationExample is a smart contract implemented in Solidity that demonstrates the usage of `require()`, `assert()`, and `revert()` statements in a calculation scenario. The contract allows performing addition, subtraction, and division operations on unsigned integers.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Prerequisites

- Solidity compiler version ^0.8.0

## Getting Started

To get started with this contract, follow the instructions below:

1. Install the Solidity compiler, if you don't have it already.
2. Compile the contract using the Solidity compiler.
3. Deploy the contract to an Ethereum network of your choice.

## Contract Details

### CalculationExample

The `CalculationExample` contract provides three functions: `add()`, `subtract()`, and `divide()`. These functions showcase the usage of `require()`, `assert()`, and `revert()` statements.

#### Functions

- `add()`: This function performs addition on the input parameters `a` and `b`. It uses `require()` to validate that both `a` and `b` are greater than zero. If any of the conditions fail, the function reverts the transaction with an error message.

- `subtract()`: This function performs subtraction on the input parameters `a` and `b`. It uses `assert()` to check if `a` is greater than or equal to `b`. If this condition fails, indicating an internal error, the function reverts the transaction.

- `divide()`: This function performs division on the input parameters `a` and `b`. It uses `revert()` to handle the case where `b` is zero. If `b` is zero, the function reverts the transaction with an error message.

### Result

The `result` variable of type `uint256` stores the calculated result of the operations performed by the contract's functions. It is a public variable, meaning it can be accessed and read by external parties.

## Usage

To use this contract, follow these steps:

1. Deploy the `CalculationExample` contract to an Ethereum network.
2. Call the `add()`, `subtract()`, or `divide()` functions with appropriate input parameters to perform the desired operation.
3. Retrieve the `result` variable to obtain the calculated result of the operation.

**Note:** The `require()`, `assert()`, and `revert()` statements ensure input validation and handle potential errors or internal inconsistencies during the calculations.

## Contributing

### L Santhosh Kumar

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
