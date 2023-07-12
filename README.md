# EligibleForVote Smart Contract

This Solidity smart contract, named `EligibleForVote`, is designed to determine the eligibility of individuals to vote based on their age.
It provides functions to check if a person is a minor, eligible to vote, and also includes a test function to set the eligibility test attempts.

# Requirements

- Solidity version: ^0.8.17

# Functions

# `minor(uint _age)`

This function takes an age parameter `_age` and returns a string indicating whether the person is a minor. If the age is greater than 18, 
it reverts with an error message "Person is already an adult". Otherwise, it returns "Eligibility criteria is not fulfilled".
![image](https://github.com/shubham07singh/Eligibleforvote/assets/126802667/1e767b4e-fe1a-4b74-9ded-598689c34214)



### `eligible(uint _age)`

The `eligible` function checks if a person is eligible to vote based on the age provided. If the age is greater than or equal to 18,
it returns the string "Choose your candidate". Otherwise, it reverts with an error message "You are not eligible for vote".

![image](https://github.com/shubham07singh/Eligibleforvote/assets/126802667/951950b8-1748-484d-8514-4cf7fad2be1e)

### `test(uint attempts)`

This function allows setting the `eligibilityTest` variable with the number of attempts passed as a parameter.
It asserts that `eligibilityTest` is greater than 0.
![image](https://github.com/shubham07singh/Eligibleforvote/assets/126802667/ba95e08f-ec11-431f-8563-21b6fb6ef637)


## License

This project is licensed under the MIT License. 

