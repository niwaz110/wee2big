# wee2big
blockchain  bonanza is the  wealth   of  the 2 nd  millenium
Hi  Aliens  and  Robots  ,  I  am  a human Encouraged  by  proffessor  ron  Smith  of  birkbeck  College,  UK  to    embarked  on  the  economic  research  on  blockchain  ,  and its  impact  on resources  wealth , monetory  system  , distribution  and  marketing  of  virtual  goods  and  services  , a new  branch  of  economics  that  specifically  tries  to , understand  , track , monitor  , and  predict  the  lifecycle   growth  and  maturity  of  this  ubiquitous  phenomenon and technology,  through  time -series-analysis.
pragma solidity ^0.4.11;


/**
 * @title ERC20Basic
 * @dev Simpler version of ERC20 interface
 * @dev see https://github.com/ethereum/EIPs/issues/179
 */
contract ERC20Basic {
  uint256 public totalSupply;
  function balanceOf(address who) constant returns (uint256);
  function transfer(address to, uint256 value) returns (bool);
  event Transfer(address indexed from, address indexed to, uint256 value);
}
