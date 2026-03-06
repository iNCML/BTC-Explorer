# Bitcoin Education Explorer

This repository contains interactive, static HTML demos for learning Bitcoin internals, especially around address encoding, signatures, balances, and transaction signing/verification.

## Projects

- `index.html`: entry page linking to all demos.
- `btc-balance.html`: **BTC Balance Checker** for checking balance data for a Bitcoin address.
- `btc-address-encoding.html`: interactive exploration of BTC address encoding methods.
- `btc-signature-lab/`: signature-focused lab (ECDSA and Schnorr concepts/steps).
- `btc-transactions/`: step-by-step transaction preimage construction, signing, and verification (supports `P2WPKH` and `P2WSH`).
- `btc-wallet-generation.html`: interactive wallet flow from entropy and mnemonic to PBKDF2 seed, then child and grand-child address derivation.
- `btc-block-management.html`: interactive block-management flow including random tx creation, Merkle tree, PoW mining, block serialization, and partial Merkle proof verification.

## Run Locally

These are static pages, so no backend is required.

1. Open `index.html` in a browser.
2. Navigate to the tool you want to use.

Optional:

- Serve via a local static server if you prefer (for example, `python3 -m http.server` from the repo root).

## Notes

- The repository also includes a GitHub Actions workflow in `.github/workflows/jekyll-docker.yml`.
- Some pages include bundled frontend assets under `assets/`.
