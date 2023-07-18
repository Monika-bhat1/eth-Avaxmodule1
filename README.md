# eth-Avaxmodule1
For this project we have to make a smart contract that implements the following functions:
require(), assert(), revert().
 1.Require: The require statement is used to validate certain conditions before proceeding with the execution of a function. If the condition evaluates to false, the 
 execution is immediately halted, and any changes made to the state are reverted. It is typically used for input validation and to ensure specific conditions are met.

 2.Assert: The assert statement is used to check for conditions that should never evaluate to false. It is used to validate internal consistency or invariants of the 
 contract. If the condition provided to assert evaluates to false, it signifies a critical error in the code, and the execution is halted. It helps catch logical 
 errors during development and testing.

 3.Revert: The revert statement is used to flag an error and revert the current transaction. It is often used when encountering unexpected or invalid states where 
 there is no safe way to proceed. When revert is triggered, all changes made to the state within the transaction are undone, and any Ether sent along with the 
 transaction is returned. It is essential for preventing erroneous states and preserving the integrity of the contract.

 In summary, require is used for input validation and conditional checks, assert is used for internal consistency and catching critical errors, and revert is used to 
 flag and revert transactions when encountering unexpected or invalid states. Each statement serves a specific purpose in handling different types of errors and 
 ensuring the integrity of the contract.

# DEPLOYMENT AND COMPILATION :
We compiled the following contract using the Remix ide environment because of its ease of working and compilation .
The contract here checks whether the owner of the contract is the sender or not .In other words we can say that the one who has created the contract is the one who uses it. We have created a constructor and three different functions that perform the same task but using different statements. 
