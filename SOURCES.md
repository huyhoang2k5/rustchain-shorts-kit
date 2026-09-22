# Factual Sources and Repository Citations
Every claim in this package is strictly grounded in the official RustChain codebase and live public endpoints.

1. **Proof-of-Antiquity Multiplier and 1 CPU 1 Vote Mechanics:**
   - Source: `scripts/rip_200_round_robin_1cpu1vote.py` in `Scottcjn/rustchain-bounties`
   - Invariant: Vintage hardware (e.g. PowerPC G4, early x86) earns higher antiquity multipliers against modern cloud virtual machines.

2. **Live Consensus Node and Tokenomics:**
   - Endpoint: `https://50.28.86.131/tokenomics`
   - Status: HTTP 200, Active Epochs, 410,448 circulating RTC tokens across 1,700+ holders.

3. **Autonomous Attestation and Sub-Second Settlement:**
   - Endpoint: `https://50.28.86.131/attest/submit`
   - Verification: Sub-second response validation for hardware entropy and AST patches.

4. **Canonical Wallet and Automatic Agent Settlement:**
   - File: `docs/CLAIMANTS.md` and `scripts/bounty_payout.py` in `Scottcjn/rustchain-bounties`
   - Mechanism: Function `_load_canonical_wallets()` parses native `RTC[0-9a-fA-F]{40}` addresses for automated payout dispatch.
