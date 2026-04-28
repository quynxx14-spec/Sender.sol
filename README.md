# Sender.sol
Sender.sol
pragma solidity ^0.8.20;
contract Sender {
    function getSender() public view returns(address) {
        return msg.sender;
    }
}
