# CodeAlpha_Simple-Storage-Smart-Contract
CodeAlpha Internship Task 1
Source Code-
    
    // SPDX-License-Identifier: MIT
    pragma solidity ^0.8.0;
     contract SimpleStorage {
    int public value;
    function increment() public {
        value += 1;
    }
    function decrement() public {
        value -= 1;
      }
    }
