# VAULTI

React + Vite website with browser-wallet connection and real BNB balance reading on BNB Smart Chain.

## Run locally

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

Deploy the resulting `dist` directory to a static host.

## Available features

- Responsive landing page and VAULTI brand assets
- Injected browser-wallet discovery, including EIP-6963
- Wallet connection, account and network change handling
- BNB Smart Chain switching and native BNB balance refresh
- Address copying and BscScan links

Open the site in a browser with an EVM wallet extension, or in a compatible wallet browser. No private keys, token approvals, deposits or transaction signatures are requested.

Agent accounts, autonomous trading, spending-limit contracts and an MCP backend are not implemented. Related landing-page sections describe the planned product.
