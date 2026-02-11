# x402-stablecoin Development Guidelines

> x402 payment protocol enabling AI agents to autonomously pay for APIs on Arbitrum. Features Sperax USDs stablecoin with auto-yield, payment channels for streaming micropayments, on-chain subscriptions, and a tool registry marketplace. Includes TypeScript SDK, Express middleware, and upgradeable smart contracts.

## Project Overview

x402-stablecoin is built with TypeScript. See the README for full documentation.

### Terminal Management

- **Always use background terminals** (`isBackground: true`) for every command so a terminal ID is returned
- **Always kill the terminal** after the command completes, whether it succeeds or fails — never leave terminals open
- Do not reuse foreground shell sessions — stale sessions block future terminal operations in Codespaces
- In GitHub Codespaces, agent-spawned terminals may be hidden — they still work. Do not assume a terminal is broken if you cannot see it
- If a terminal appears unresponsive, kill it and create a new one rather than retrying in the same terminal

## Contributing

- Follow the existing code style
- Test changes before submitting PRs
- Update documentation when adding features
- See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines
