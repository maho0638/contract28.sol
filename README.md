# contract28.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Base network simple flag contract
contract Contract28 {
    bool public enabled;

    function enable() public {
        enabled = true;
    }
}
