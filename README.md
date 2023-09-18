# Smart Contract: funcErrors

This is a Solidity smart contract that demonstrates error-handling mechanisms using the `require`, `revert`, and `assert` statements. The contract showcases how to restrict access to certain actions and handle errors gracefully within Ethereum smart contracts.

## Features

- `testRequire`: A function that allows the contract owner to set a numeric value and ensures that only the owner can perform this action using the `require` statement.

- `testRevert`: A function that demonstrates the use of the `revert` statement to revert transactions if an input condition is not met. It checks whether the input is greater than 10 and reverts if it's not.

- `testAssert`: A function that uses the `assert` statement to check a condition and revert if it fails. It verifies that a numeric input is not zero.

## Usage

1. Deploy the `funcErrors` smart contract to your Ethereum network.

2. Interact with the contract by calling its functions:

   - `testRequire`: Set a numeric value, but only if you are the owner.

   - `testRevert`: Attempt to send an input greater than 10, and observe the revert behavior.

   - `testAssert`: Supply a non-zero input to see the assert behavior.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Note:** Replace `'LICENSE'` with the actual path to your license file.
