# [Project Name Placeholder]

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque euismod, urna eu tincidunt consectetur, nisi nisl aliquam nunc, vitae euismod nisl nunc euismod nunc.

---

## Description

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque euismod, urna eu tincidunt consectetur, nisi nisl aliquam nunc, vitae euismod nisl nunc euismod nunc.

---

## Supported MCP Servers and Their Capabilities

### 1. [**Base MCP Server**](https://github.com/base/base-mcp)

A Model Context Protocol (MCP) server for the Base Network and Coinbase API, enabling AI applications to interact with Base for wallet management, token operations, contract deployment, NFTs, onramping, and more.

**Available Tools:**

- `get-address`: Retrieve your wallet address.
- `list-balances`: List all balances for your wallet.
- `transfer-funds`: Transfer funds to another address.
- `deploy-contract`: Deploy a smart contract.
- `check-address-reputation`: Check the reputation of an address.
- `get_morpho_vaults`: Get Morpho vaults for a given asset.
- `call_contract`: Call a contract function.
- `get_onramp_assets`: List onramp assets for a region.
- `onramp`: Get a URL for onramping funds.
- `erc20_balance`: Get ERC20 token balance.
- `erc20_transfer`: Transfer ERC20 tokens.
- `list_nfts`: List NFTs owned by an address.
- `transfer_nft`: Transfer an NFT (ERC721/1155).
- `buy_openrouter_credits`: Buy OpenRouter credits with USDC.

---

### 2. [**Berachain MCP Server**](https://github.com/PlayAINetwork/bera-mcp)

An MCP server for AI agents to interact with the Berachain blockchain, supporting wallet, token, transaction, and block operations.

**Available Tools:**

- `getBalance`: Get all token balances for a wallet.
- `getTokenInfo`: Get detailed ERC20 token information.
- `getTokenSupply`: Get total supply for an ERC20 token.
- `getTransactionData`: Get detailed transaction information.
- `getBlockInfo`: Get information about a block by hash.

---

### 3. [**Abstract Chain MCP Server**](https://github.com/PlayAINetwork/abstract-mcp)

A Model Context Protocol (MCP) server for the Abstract Chain blockchain, providing wallet, token, transaction, and block data tools.

**Available Tools:**

- `getWalletBalance`: Get native and ERC20 token balances for a wallet.
- `getTokenSupply`: Get total supply for an ERC20 token.
- `getTokenInfo`: Get detailed ERC20 token information.
- `getTransactionData`: Get transaction and receipt data.
- `getBlockInfo`: Get information about a specific block.

---

### 4. [**BNBChain MCP (Binance Smart Chain Tool Server)**](https://github.com/TermiX-official/bsc-mcp)

A plug-and-play MCP tool server for Binance Smart Chain (BSC), supporting native/BEP-20 transfers, contract interaction, token deployment, PancakeSwap, and more.

**Available Tools:**

- `transferNativeToken`: Send BNB to a wallet.
- `transferBEP20Token`: Transfer BEP-20 tokens.
- `pancakeSwap`: Swap tokens via PancakeSwap.
- `createFourMeme`: Create meme tokens on Four.Meme.
- `createBEP20Token`: Deploy a BEP-20 contract.
- `getBalance`: Get token and native balance.
- `callContractFunction`: Custom contract calls via ABI.
- `getWalletInfo`: Get wallet info for an address.
- `securityCheck`: Check token security.
- `pancakeAddLiquidity`: Add liquidity to PancakeSwap.
- `pancakeMyPosition`: View PancakeSwap positions.
- `pancakeRemovePosition`: Remove liquidity from PancakeSwap.
- `sellMemeToken`: Sell meme tokens on Four.Meme.

---

### 5. [**EVM Agent Kit MCP**](https://github.com/mcp-dao/evm-agent-kit)

An open-source toolkit for connecting AI agents to EVM-compatible blockchains, supporting token operations, DeFi, market data, and social data.

**Available Tools**

- `getErc20Balance`: Check ERC20 token balances
- `transferErc20`: Transfer ERC20 tokens
- `createFourMemeToken`: Launch tokens on Four.meme
- `getTokenPriceData`: Get token pricing data (CoinGecko)
- `getTrendingTokens`: Fetch trending tokens
- `getTopGainers`: Monitor market movements
- `getProtocolTvl`: Access DeFi protocol TVL (DeFiLlama)
- `supply`: Supply assets to DeFi protocols (e.g., Compound)
- `bridgeTokens`: Bridge tokens across chains
- `elfaAiApi`: Social media insights and trending tokens

---

### 6. [**Solana Agent Kit MCP**](https://github.com/sendaifun/solana-agent-kit)

An open-source toolkit for connecting AI agents to Solana, supporting 60+ actions including token trading, NFT management, DeFi, airdrops, bridging, and more.

**Available Tools**

- `TRADE`: Trade tokens (Jupiter Exchange)
- `LAUNCH_PUMPFUN_TOKEN`: Launch new tokens (Pump.fun)
- `LEND_ASSET`, `LULO_LEND`: Lend assets (Lulo)
- `COMPRESSED_AIRDROP`: Send compressed airdrops
- `EXECUTE_BLINK`: Execute blinks
- `CREATE_OPENBOOK_MARKET`, `CREATE_METEORA_DLMM_POOL`, `CREATE_METEORA_DYNAMIC_AMM_POOL`, `RAYDIUM_CREATE_AMM_V4`, `RAYDIUM_CREATE_CLMM`, `RAYDIUM_CREATE_CPMM`, `CREATE_ORCA_SINGLE_SIDED_WHIRLPOOL`: Launch tokens on AMMs
- `SWAP`, `DEBRIDGE_CREATE_BRIDGE_ORDER`, `DEBRIDGE_EXECUTE_BRIDGE_ORDER`: Bridge tokens across chains (Wormhole, deBridge, Mayan)
- `DEPLOY_COLLECTION`, `DEPLOY_TOKEN`, `DEPLOY_TOKEN_2022`, `MINT_NFT`, `LIST_NFT_FOR_SALE`, `CANCEL_NFT_LISTING`, `CREATE_3LAND_COLLECTIBLE`, `GET_ASSET`, `GET_ASSETS_BY_AUTHORITY`, `GET_ASSETS_BY_CREATOR`, `SEARCH_ASSETS`: NFT creation and management (Metaplex, 3.Land)
- `LEND_ASSET`, `LULO_LEND`, `LULO_WITHDRAW`, `WITHDRAW_ALL_MANIFEST_FUNDS`, `PLACE_MANIFEST_LIMIT_ORDER`, `CANCEL_ALL_MANIFEST_ORDERS`, `CREATE_MANIFEST_MARKET`, `GET_LIMIT_ORDER_HISTORY`, `GET_OPEN_LIMIT_ORDERS`, `CREATE_LIMIT_ORDER`, `CANCEL_LIMIT_ORDERS`, `GET_PROTOCOL_TVL`, `GET_TOP_GAINERS`, `GET_TPS`, `AVAILABLE_DRIFT_MARKETS`, `CREATE_DRIFT_USER_ACCOUNT`, `CREATE_DRIFT_VAULT`, `DEPOSIT_INTO_DRIFT_VAULT`, `DEPOSIT_TO_DRIFT_USER_ACCOUNT`, `DRIFT_USER_ACCOUNT_INFO`, `TRADE_DRIFT_PERP_ACCOUNT`, `TRADE_DELEGATED_DRIFT_VAULT`, `DRIFT_SPOT_TOKEN_SWAP_ACTION`, `STAKE_TO_DRIFT_INSURANCE_FUND_ACTION`, `REQUEST_WITHDRAWAL_FROM_DRIFT_VAULT`, `WITHDRAW_FROM_DRIFT_VAULT`, `WITHDRAW_OR_BORROW_FROM_DRIFT_ACCOUNT`, `UPDATE_DRIFT_VAULT`, `UPDATE_DRIFT_VAULT_DELEGATE_ACTION`, `UNSTAKE_FROM_DRIFT_INSURANCE_FUND_ACTION`, `DRIFT_GET_ENTRY_QUOTE_OF_PERP_TRADE_ACTION`, `DRIFT_GET_LEND_AND_BORROW_APY_ACTION`, `DRIFT_PERP_MARKET_FUNDING_RATE_ACTION`, `REQUEST_UNSTAKE_FROM_DRIFT_INSURANCE_FUND_ACTION`, `DRIFT_VAULT_INFO`, `DOES_USER_HAVE_DRIFT_ACCOUNT`, `DERIVE_DRIFT_VAULT_ADDRESS_ACTION`, `DEPOSIT_TO_DRIFT_USER_ACCOUNT`: DeFi integrations (Jupiter, Raydium, Orca, Drift, Meteora, Openbook)
- `FETCH_PRICE`, `PYTH_FETCH_PRICE`, `GET_TOKEN_DATA`, `GET_TOKEN_DATA_OR_INFO_BY_TICKER_OR_SYMBOL`, `GET_SANCTUM_PRICE`, `GET_SANCTUM_APY`, `GET_SANCTUM_TVL`, `GET_TPS`: Market data (CoinGecko, Pyth, Allora, Switchboard, Sanctum)
- `STAKE_WITH_JUPITER`, `STAKE_WITH_SOLAYER`: Stake SOL (JupSOL, Solayer)
- `PARSE_INSTRUCTION`, `PARSE_ACCOUNT_DATA`: Parse instruction/account data
- `SANCTUM_ADD_LIQUIDITY`, `SANCTUM_REMOVE_LIQUIDITY`, `SANCTUM_SWAP_LST`, `SANCTUM_GET_OWNED_LST`: Sanctum LST operations (price, APY, TVL, liquidity, swap)
- `BALANCE_ACTION`, `TOKEN_BALANCE_ACTION`: Get wallet/token balances
- `TRANSFER`: Transfer tokens or SOL
- `REQUEST_FUNDS`: Request SOL from faucet (devnet/testnet)
- `CLOSE_EMPTY_TOKEN_ACCOUNTS`, `SOLUTIOFI_BURN_TOKENS`, `SOLUTIOFI_SPREAD_TOKEN`, `SOLUTIOFI_CLOSE_ACCOUNTS`, `SOLUTIOFI_MERGE_TOKENS`: Wallet and token account management
- `WALLET_ADDRESS`: Get your wallet address

---
