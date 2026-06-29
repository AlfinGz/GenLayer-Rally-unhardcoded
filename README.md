# GenLayer RALLY - unhardcoded.com Contribution

## Campaign: The First Dispute - unhardcoded.com
Author: @AlfinGz
Date: juni 2026

### Summary
This repo documents my contribution to the GenLayer RALLY campaign. 
Topic: Explaining `unhardcoded.com` as a runtime policy layer for LLMs.

### Key Concept: Why Unhardcoded?
Instead of hardcoding `model="gpt-4"`, `unhardcoded` uses policies at runtime to:
1.  **Filter**: Remove models that fail your rules
2.  **Rank**: Score remaining models by performance/cost  
3.  **Route**: Select the cheapest model that still passes
4.  **Resilient**: Auto-failover + replayable traces for transparency

Hardcoding = technical debt. Expensive, single point of failure, no flexibility.
Runtime Policy = production-ready LLM infra.

### On-Chain Proof
- **GenLayer Testnet TX**: https://explorer-rally-testnet.genlayer.com/tx/0x4d548e690cf000a700e735916e1bea72fe159950067bb530ffad9c341bb2faa9
- **Method Called**: `submit_Tweet`
- **Status**: `FINALIZED` / `SUCCESS`
- **Tweet**: https://x.com/Xyz_Alfin/status/2071121955236037045

### Tweet Content
"Still hardcoding `model=\"gpt-4\"` in prod? 
@GenLayer built unhardcoded.com — a runtime policy layer for LLMs. 
Stop hardcoding. Start routing. 
unhardcoded.com 
"
