## Panoptic

- "SemiFungiblePositionManager" a gas-efficient alternative to Uniswap's NFPM. 
- Manages complex, multi-leg swap positions.
- Positions are encoded in ERC1155 tokenids.
- Performs swaps allowing users to mint positions with a single token type.
- Critically, it supports minting of both typical LP positions.
- Standard LP positions where liquidity is added to Uniswap and long positions where liquidity is burned.
- Scoped code represents a subsection of the POp v1 protocol, but also serves as a standalone liquidity manager open for use by any entity.

- Multi-leg strat: A strat that involves more than one trading action or order. e.g. instead of a singular transaction, a multi-leg position combines several trades into one composite strategy.
- In multi-leg strats, each trade//leg plays a unique role.
- The combined effect of the trades is designed to achieve a specific goal. e.g. Long straddle.
- Long straddle: Buy a call option, and buy a put option in one composite execution. This is a multi-leg strat because it involves two distinct operations being combined and executed as a singular entity.
- ERC-1155: Can represent both fungible tokens and NFT's, enables batch transfers of multiple token types in a single transaction, tokens are identified by a unique ID and stored together in a single contract unlike ERC-721 where each NFT is a separate contract, can embody conditional fungibility.
-  
