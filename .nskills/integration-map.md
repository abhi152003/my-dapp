# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`965cd30e`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`c60a7c94`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`c60a7c94`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`2371855b`)
  
