"# BEP20-Presale-Vesting-Contract" 

BEP20 token presale and vesting contract:

deposit BNB
distributed Token

ratio BNB/Token 

Softcap - settable after deployment
Hardcap - settable after deployment

startBlock - settable after deployment
endBlock - settable after deployment

Wallet Softcap - settable after deployment
Wallet Hardcap - settable after deployment

Vesting emission rate - settable after deployment

Token first distribution blok - settable after deployment

Block period for next distributions 
as long as all tokens will be distributed - settable after deployment

BNB claim function if softcap not reached

BNB claim function if hardcap  reached - contract owner or  settable address

Token claim function if softcap not reached - contract owner or  settable address

In order to be sure of the distribution of all tokens, we should deposit more than the assumed amount in the contract.

Not distributed Tokens claim function (after ends of distribution if their quantity remains on the contract less than planned for distribution. Unless that can be solved by an emergency withdraw )

BNB emergency withdraw
Token emergency withdraw


https://forum.openzeppelin.com/t/openzeppelin-upgrades-step-by-step-tutorial-for-hardhat/3580

Presale (softcap, hardcap)
vesting( emission rate, token first distribution block, block period for next distributions)
