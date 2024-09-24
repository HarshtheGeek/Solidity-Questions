# Solidity-Questions
This repository includes all the Practice questions of solidity.

# Solidity Storage

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StorageContract {

    uint256 private Value;

    // Function to store a new value
    function storeValue(uint256 _newValue) public {
        Value = _newValue;
    }

    // Function to read the stored value
    function readValue() public view returns (uint256) {
       return Value;
    }
}

```

# Solidity Factorial

```


```
