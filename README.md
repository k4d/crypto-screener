# crypto-screener

CryptoScreener is a real-time cryptocurrency analysis terminal, providing global market statistics, information on trending tokens, a searchable token table, and a comprehensive token detail page including charts, real-time prices, and exchange data. It operates using CoinGecko REST API interfaces and a WebSocket API for real-time market data streaming with sub-second latency — offering everyone the opportunity to build advanced, data-driven crypto and Web3 projects.

## Getting Started

### Installation

To install dependencies, run the following command in the root directory:
```bash
bun install
```

### Running the Application

To run both the frontend and backend applications concurrently, use the following command in the root directory:
```bash
bun run dev
```

For specific parts:
```bash
bun run dev:client # Runs Astro frontend development server
bun run dev:server # Runs Hono backend development server
```
