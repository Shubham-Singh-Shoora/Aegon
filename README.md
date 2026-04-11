# ZK Voting DAO

A full-stack zero-knowledge DAO voting prototype with Noir proofs, Solidity contracts, an off-chain eligibility builder, and a React frontend.

## Structure

- `frontend/`: voter and proposer web app (React + Vite)
- `off-chain/`: eligibility tree and voter credential artifact generator
- `on-chain/contracts/`: Solidity contracts and deployment scripts (Foundry)
- `zk_proof/`: Noir circuit and proving artifacts
