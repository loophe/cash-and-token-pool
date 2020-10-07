# cash and token pools

[![Build Status](https://travis-ci.com/vittominacori/erc20-generator.svg?branch=master)](https://travis-ci.com/vittominacori/erc20-generator)
[![Coverage Status](https://coveralls.io/repos/github/vittominacori/erc20-generator/badge.svg?branch=master)](https://coveralls.io/github/vittominacori/erc20-generator?branch=master)
[![MIT licensed](https://img.shields.io/github/license/vittominacori/erc20-generator.svg)](https://github.com/vittominacori/erc20-generator/blob/master/LICENSE)

A simple Smart Contract generator for a Standard, Capped, Mintable, Burnable, Payable ERC20 Token.

Token has a Role Based Access Control so you can add the `MINTER` permission to users or Smart Contracts.

Token has a `trasferEnabled` property. Nobody can transfer tokens until the property will be enabled or you can define users as `OPERATOR` allowed to transfer also if not enabled.

Token has the ERC1363 behaviors. [ERC1363](https://eips.ethereum.org/EIPS/eip-1363) is an ERC20 compatible token that can make a callback on the receiver contract to notify token transfers or token approvals.

Token extends from [ERC20Base](https://github.com/vittominacori/erc20-token).

DApp source here [https://github.com/vittominacori/erc20-generator/tree/dapp](https://github.com/vittominacori/erc20-generator/tree/dapp).


## Try it

[https://vittominacori.github.io/erc20-generator](https://vittominacori.github.io/erc20-generator)
