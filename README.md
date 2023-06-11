## Introduction

Solidity, the primary language for developing smart contracts on blockchain platforms like Celo, offers a variety of data types including Structs and Mappings, which can be used to create more complex and powerful contracts. In this challenge, you will delve into advanced data structures in Solidity by creating a user registration system.

## Problem Statement

Design a smart contract that simulates a user registration system with the following requirements:

1. The contract should allow users to register with their username and a password. The password should be hashed before being stored.
2. The contract should use a struct to represent each user, with attributes for the username, hashed password, and registration date.
3. The contract should use a mapping to link usernames with their respective user data.
4. The contract should allow anyone to check if a username is already registered.
5. The contract should prevent the same username from being registered more than once.

## Hints

- Use the keccak256 function to hash passwords before storing them.
- Use the `now` global variable to record the registration date.
- Use `msg.sender` to identify the address that is interacting with the contract.
- Use `require` statements to enforce that a username is not already taken.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and meet all the requirements.
- **Readability**: The contract should be well-documented, with comments explaining the code.
- **Testability**: You should also provide examples of how to test each function of the contract.

Remember, this challenge is a simple exercise and does not include all the best practices needed for a secure, real-world user registration system.

For a comprehensive understanding of Celo smart contracts and Solidity, please refer to the Celo and Solidity documentation.

## Submission

Please reply with a link to your PR on GitHub, including your user registration contract. Also, include any notes or comments you think are necessary to understand your design and choices. Lastly, provide a brief explanation about how each function of the contract should be tested.
