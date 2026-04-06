# UserBalances.sol
UserBalances.sol6
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract UserBalances {
    mapping(address => uint) public balances;

    function setBalance(uint _amount) public {
        balances[msg.sender] = _amount;
    }
}
Create storage and utility contracts
Clean code formatting
