# Decentralized-Lottery-system
Solidity smart contract for decentralized lottery system. 


About the contract:
- Consturctor to assign owner.
- A address type payable array comtaining the addresses of participants.
- Contract is valid only if number of participants >=3
- Minimum transaction per participation = 1 ether
- Selecting the winner using keccak256 from the partipants array
- Tranferring all the funds from contract address to selected winner's address.
- Contract functions like checking lottery funds, selecting random winner, are only accessable to the owner of the contract.
