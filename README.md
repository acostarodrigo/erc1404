# ERC1404 Test

A simple ERC-1404 contract modified to run over solc compiler 0.5.0

Wanted to generate this test because most implementation I see are detached from openzeppelin-solidity standards.

## MyTestToken

The token Inherits only SimpleRestrictedToken contract.

```
MyTestToken -->
               SimpleRestrictedToken -->
                                        ERC20```
