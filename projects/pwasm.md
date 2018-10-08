# PWASM

Relevant repos: <br>
* [pwasm tutorial](https://github.com/paritytech/pwasm-tutorial)
* [pwasm erc20 example](https://github.com/paritytech/pwasm-token-example)
* [pwasm repo contract](https://github.com/paritytech/pwasm-repo-contract)

The next relevant project should be to consider what crypto collectibles exist and consider how to implement them via pwasm.

Seems as if the relevant standards to incorporate include: <br>
* ERC20 which is implemented above
* [ERC 165](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-165.md) which supports interfacing token standards
* [ERC 721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md)
* [ERC 998](https://github.com/ethereum/EIPs/issues/998)

So a good project is implementing these token standards on pwasm (which shouldn't be ridiculously difficult if I can wrap my head around the relevant repos code above).
