# Scroll-NEW-ERC-20
ANIKA Token ERC-20 from Remix 

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.4;
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
contract ANIK is ERC20 {
    constructor() ERC20("ANIKA", "ANKA") {
        _mint(msg.sender, 1000 * 10 ** decimals());
    }
}
