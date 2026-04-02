# Boolean-Toggle-3
Boolean Toggle.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Toggle {
    bool public isOn;

    function toggle() public {
        isOn = !isOn;
    }
}
