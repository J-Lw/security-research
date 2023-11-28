## Panoptic

- "SemiFungiblePositionManager" a gas-efficient alternative to Uniswap's NFPM. 
- Manages complex, multi-leg swap positions.
- Positions are encoded in ERC1155 tokenids.
- Performs swaps allowing users to mint positions with a single token type.
- Critically, it supports minting of both typical LP positions.
- Standard LP positions where liquidity is added to Uniswap and long positions where liquidity is burned.
- Scoped code represents a subsection of the POp v1 protocol, but also serves as a standalone liquidity manager open for use by any entity.
