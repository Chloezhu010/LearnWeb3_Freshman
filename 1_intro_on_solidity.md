# Variables & Types
## 3 types of variables
1. Local: inside a function, not stored on chain
2. State: outside a function to maintain global state within the contract, stored on chain
3. Global: info about the chain

## Different variables
1. Uint: unsigned integer, non-negative integers

    uint8: 0 to 255
    uint256: 0 to 2^256 - 1
2. Int: signed integer, negative integers
    
    int8: -128 to 127
3. Address: 160-bit value, represents an Ethereum address
    
    address: 0x1234567890abcdef1234567890abcdef12345678
4. Bool: true or false
    
    default value: false

# Functions, Loops, and If/Else
1. public: can be called by anyone
2. view: can only read state variables, don't require gas
3. private: can only be called by the contract
4. internal: can only be called by the contract and its parent contracts
5. external: can only be called by other contracts

# Arrays, Strings
1. arrays: fixed or dynamic size array
2. string: dynamic size string

# Storage
1. memory: temporary variable, not stored on chain, only exists in the function
2. storage: permanent variable, stored on chain, exists for the lifetime of the contract



# Solidity documentation
https://docs.soliditylang.org/en/v0.8.26/