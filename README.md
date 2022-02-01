
Init Process Flow:

Seeds - Proposal Grove 

Flows:
Connect wallet
Function giveSeeds 
	◦	Hit button for seeds
	◦	Send 10 seeds to msg.sender
	◦	Maybe Add wallet to list to keep balance of seeds dispensed
Function createProp
	◦	Send 1 seed with txt idea of proposal
	◦	Msg.sender balance ==-1
	◦	Add proposal to billboard
Function Accept Proposal
	◦	Contract owner can accept proposals and return 2 seeds
	◦	Add text for funding, other details 


	◦	Contract setup in openzeplin wizard
	◦	Mint 10k SEEDS as ERC20 or 1155

Test Steps
	◦	Contract is payable 
	◦	Wallet can receive seeds
	◦	SubmitProposal should be 1 seed
	◦	Accept Proposals should return 2 seeds
	◦	


Future Ideas:
	◦	Use seeds for purchases 
	◦	Integrate ETH payment into the approveProposal so people gets Seeds and ETH on the same step or a following step. 


//****
//OLD SimpleBank Readme.md




# Simple Bank Exercise

SimpleBank is a [Truffle](https://www.trufflesuite.com/) project that contains
a starter contract,
[migration](https://www.trufflesuite.com/docs/truffle/getting-started/running-migrations#migration-files)
and [Truffle JavaScript test
files](https://www.trufflesuite.com/docs/truffle/testing/writing-tests-in-javascript).
In this exercise you are going to implement the SimpleBank.sol contract.

## Files

  * `contracts/SimpleBank.sol`
    : the partial implementation of a Solidity Contract you will complete. 
  * `test/simpleBank.test.js`
    : the Truffle test file that describes the behavior of a correct SimpleBank
    contract.

## Requirements
  1. Latest truffle version.
     ```console
     npm -g uninstall truffle && npm -g install truffle
     ```
  1. Your preferred code editor.
  1. Familiarity with terminals.

## Instructions

Follow the comments outlined in SimpleBank.sol to implement its
functionality. The test are there to determine correct contract behavior as
well as guide you through the implementation. 

The general workflow is to use Test Drive Development's red green process:
  1. Run `truffle test` from a terminal.
  2. Use the failed test output along with the hints in
     `contracts/SimpleBank.sol` to make the test pass.

<!-- <details><summary>Video: Run a test example</summary>

[![asciicast](https://asciinema.org/a/u3oXwF8qKruSN81sm8MGsmTf0.png)](https://asciinema.org/a/u3oXwF8qKruSN81sm8MGsmTf0)

</details> -->

