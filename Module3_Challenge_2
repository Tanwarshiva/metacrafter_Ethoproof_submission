// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleContract {
    uint public OneWei = 1 wei;
    uint public OneEther = 1 ether;
    uint public OneGwei = 1 gwei;

    function testOneWei() public pure returns (bool) {
        return 1 wei == 1;
    }

    function testOneEther() public pure returns (bool) {
        return 1 ether == 1e18 wei;
    }
    
    function testOneGwei() public pure returns (bool) {
        return 1 wei == 1e9 gwei;
    }
}
