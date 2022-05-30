# ETH-Validators-List
List of Addresses that Deposited the Ethereum Beacon Chain Contract 


**Contracts** 

Eth2 Deposit Contract

0x00000000219ab540356cbb839cbe05303d7705fa

RPL node Deposit contract Address

0xDCD51fc5Cd918e0461B9B7Fb75967fDfD10DAe2f


**#Validator List**
All unique validators including Rocketpool node operators, this filters out exchanges such as Coinbase and kraken, and staking as a service/liquid staking such as Lido.

this list is every solo validator owned address that made at least 1 valid deposit to the beacon chain up until the end of last month. (will be keeping this updated until the merge)

**#Beacon Chain Depositors**

All unique addresses that deposited a valid (32ETH) transaction to the ‘ETH2 deposit contract’.
this will include addresses belonging to exchanges and liquid/pooled staking providers. contract addresses are excluded from this, example rocketpool minipool contract addresses 

**#Rocketpool Depositors**

All unique addresses that deposited a valid transaction to the ‘ETH2 deposit contract’ via ‘Rocketpool node deposit contract address’, these are Ethereum Validators/ Rocketpool node operators, this list excludes rETH minters.

**#Blacklist**

Data From ETHsta.com (https://github.com/Zachary-Lingle)
Known staking as a service/liquid staking addresses, Such as Lido, Stakewise. exchange addresses such as Kraken,
this includes Coinbase deposits which account for ~57,000 of the ‘Beacon Chain Depositors’ sheet. 
some addresses such as known QuadrigaCX wallets


**Methodology**

Data was pulled from Etherscan Eth2 Deposit Contract- transactions, ineligible deposits <32 were removed, all addresses extracted, and duplicate addresses filtered out.
Leaving all unique (eligible) Ethereum addresses that have deposited to the beacon chain contract to run a validator, pre- merge.
