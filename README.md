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


Transaction Hash:
0x9f05d5db932fece7a62c4677e325bf7773eae50d56e688c08cf745c6b36193f3

https://blockscout.scroll.io/tx/0x9f05d5db932fece7a62c4677e325bf7773eae50d56e688c08cf745c6b36193f3
stamp blockexplorer^11
*00x07812
