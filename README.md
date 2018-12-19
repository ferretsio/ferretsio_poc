# Ferretsio_POC

This repo contains contracts developed as part of POC for [ferretsio](www.ferrets.io).

## How to read ?

There are two entry points `election.cpp` and `ecommissioner.cpp`.

### Contract - `Election`

This contract is created as the top level abstraction to keep the anonymity of the voter. Voters can use interface associated with this contract to cast their votes.

### Contract - `Ecommissioner`

**`ecommissioner`** is the parent for both `evoters` and `ecandidates` contract. The interface can be used to add the running candidates and voters of any election distric.

### Contract - `Erecords`

This contract stores the result of the election. It can only be modified by the action raised by `Election` contract.

### Contract - `Ecandidates` and `Evoters`

These are the data stores for the lists of candidates and the voters in any district.


## HELP?

Please look at the [EOS developer portal](https://developers.eos.io/eosio-home/docs/introduction).