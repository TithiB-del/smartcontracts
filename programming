pragma solidity ^0.5.0;
contract escrowtimelock
 { address payable public buyer;
 uint256 public reltime;
 function () external payable {}
 constructor (address payable_buyer, uint256_reltime) public
 { require (_reltime > block.timestamp, "release time isnt now");
 buyer =_buyer; reltime = _reltime; }
 function release () public 
 { require(block.timestamp >= reltime, "release time has arrived");
 uint256 amount = address(this).balance;
 require ( amount> 0, "nothing to release");
 buyer.transfer(amount); } }
