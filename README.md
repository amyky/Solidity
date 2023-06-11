# Variable Contract
This contract provides a set of functions to store and retrieve different types of variables. It is built on the Ethereum blockchain using the Solidity programming language.

License
This contract is licensed under the MIT License. For more information, please see the LICENSE file.

Prerequisites
Make sure you have the following software installed:

Solidity compiler version ^0.8.18
Ethereum client or development framework
Usage
Deploy the contract to the Ethereum network.
Interact with the contract using the provided functions.
Contract Details
Variables
The contract contains the following variables:

myUint: An unsigned integer to store numerical values.
myString: A string variable to store text values.
myAddress: An Ethereum address to store the address of an account.
myBool: A boolean variable to store true/false values.
Functions
The contract provides the following functions:

setMyUint(uint _value)
Sets the value of myUint to the specified _value and returns the updated value.

Parameters:
_value: An unsigned integer representing the new value of myUint.
getMyUint()
Returns the current value of myUint.

setMyString(string memory _value)
Sets the value of myString to the specified _value and returns the updated value.

Parameters:
_value: A string representing the new value of myString.
getMyString()
Returns the current value of myString.

setMyAddress(address _value)
Sets the value of myAddress to the specified _value and returns the updated value.

Parameters:
_value: An Ethereum address representing the new value of myAddress.
getMyAddress()
Returns the current value of myAddress.

setMyBool(bool _value)
Sets the value of myBool to the specified _value and returns the updated value.

Parameters:
_value: A boolean representing the new value of myBool.
getMyBool()
Returns the current value of myBool.

Deployment
To deploy this contract, follow the standard deployment process for Ethereum contracts. Use the Solidity compiler version ^0.8.0 to compile the contract code and then deploy it to your preferred Ethereum network.

Contributors
Maureen Anunobi
If you would like to contribute to this project, please submit a pull request.

Feedback and Support
For feedback, questions, or support, please contact anunobi31@gmail.com.