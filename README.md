## ERC20 Client Execution Divergence PoC

This repository contains execution traces and client diff artifacts
demonstrating a deterministic execution divergence between clients
during a standard ERC20 flow (`mint`, `approve`, `transferFrom`).

### Observed Behavior
- Reference client executes the deterministic test case successfully.
- Target client reverts on the same test case under identical conditions.
- Execution traces and resulting state differ across clients.

### Environment
- Network: Base Sepolia
- Test case: erc20_approve_transferFrom_deterministic
- Tooling: automated client diff runner

These artifacts were generated locally and are provided for analysis.
