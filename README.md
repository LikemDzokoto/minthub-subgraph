# Overview

This subgraph indexes and tracks data from the Tokenated deployed on the Base Sepolia network. It provides real-time insights into the Marketplace's transactions and events.

## Setup

To modify or extend this subgraph:

1. Clone the repository:
   ```bash
   git clone https://github.com/LikemDzokoto/minthub-subgraph
   ```
2. Install dependencies:
   ```bash
   yarn install
   ```
3. Make your changes to the schema, mappings, or configurations.
4. Generate types:
   ```bash
   graph codegen
   ```
5. Build the subgraph:
   ```bash
   graph build
   ```
6. Deploy to The Graph:
   ```bash
   graph deploy --studio tokenated
   ```

## Cloning the Repository

To clone the repository, use the following command:
```bash
git clone https://github.com/LikemDzokoto/minthub-subgraph
```

## Installing Packages

To install the necessary packages, run:
```bash
yarn install
```

## Authenticating The Graph

To authenticate with The Graph, follow the instructions provided in the official documentation.

## Testing the Subgraph

To run tests for the subgraph, use:
```bash
yarn test
```

## Deploying the Subgraph

To deploy the subgraph, use:
```bash
graph deploy <subgraph-name>
```

## Live Query Link

You can access the live query link here: [Live Query Link](<https://api.studio.thegraph.com/query/101141/tokenated/version/latest>)
