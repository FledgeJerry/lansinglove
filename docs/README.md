# Web3 Features Outline

This document sketches out plans to add optional Web3 functionality on top of the existing Lansing.Love static site. These ideas are early and subject to change as the community provides feedback.

## FLDG Coin
- **Purpose**: A community token used to incentivize participation and support local initiatives.
- **Blockchain**: Planned deployment on the Polygon network for low fees and compatibility with Ethereum tools.
- **Usage on the Site**:
  - Allow visitors to earn FLDG by contributing verified stories or volunteering.
  - Integrate with on-chain voting for allocating community resources.

## NFT Galleries
- **Concept**: Showcase art and collectibles created by Lansing residents.
- **Technical Approach**:
  - Mint NFTs on Polygon and display them in a gallery section.
  - Most NFTs won't be sold. Instead, they serve as credentials for skills, residency, or proof of attendance. A few may remain tradable.
- **Site Integration**:
  - The main site would load metadata from the blockchain or IPFS to display artwork or credential details.
  - Interaction will remain optional, so visitors without wallets can still browse.

## Interaction with the Existing Site
1. **Static Pages with Web3 Hooks**: The current HTML/CSS pages will remain, while JavaScript modules check if a user has a compatible wallet (e.g., MetaMask). If present, additional buttons and information will appear.
2. **Progressive Enhancement**: Core content is always accessible. Web3 features add optional ways to engage but won't block access.
3. **Community Governance**: Decisions about FLDG coin usage or which NFTs to feature can be managed through Fledge DAO tools.

These outlines are a starting point. As the project grows, more detailed specs and technical designs will be added to this `docs/` directory.
