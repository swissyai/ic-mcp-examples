# ICP-MCP Examples

Full source code for 35 Internet Computer examples, curated for AI agent learning via [IC-MCP](https://github.com/your-username/ICP-MCP).

## Purpose

This repository provides complete, runnable ICP projects that AI agents can reference to learn real-world patterns. No inference needed - just actual production code.

## Structure

Each directory contains a complete ICP project with full source code:

```
llm-chatbot/
├── backend/
│   └── app.mo           # Motoko backend canister
├── frontend/            # React/Vite frontend (if applicable)
├── dfx.json             # Canister configuration
├── package.json         # Dependencies
└── README.md            # Project documentation
```

## Categories

- **AI** (3 examples): LLM chatbot, AI agents, vector databases
- **DeFi** (3 examples): Token swaps, liquidity management
- **Chain Fusion** (6 examples): Bitcoin, Ethereum, Solana integration
- **NFT** (2 examples): Minting, collections
- **Games** (3 examples): On-chain games
- **Data Storage** (6 examples): File storage, encrypted data (vetKeys)
- **Productivity** (6 examples): Task managers, planners, galleries
- **Tooling** (6 examples): HTTP outcalls, canister logs, query stats, performance

## Running Examples

Each example can be deployed locally:

```bash
cd llm-chatbot
dfx start --background
dfx deploy
```

Most examples include both Motoko and Rust versions for comparison.

## Integration with IC-MCP

AI agents using IC-MCP can:
1. **Discover** examples via metadata index (fast, lightweight)
2. **Fetch** full source on-demand from this repo
3. **Learn** from actual production patterns

Example URLs for fetching:
- `https://raw.githubusercontent.com/your-username/icp-mcp-examples/main/llm-chatbot/backend/app.mo`
- `https://raw.githubusercontent.com/your-username/icp-mcp-examples/main/llm-chatbot/dfx.json`

## Source

Examples sourced from ICP ecosystem, verified and curated for accuracy.

## License

Each example retains its original license. See individual project READMEs.
