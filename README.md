# Dev Assets for Blockchain Projects

This repository contains static assets (images and JSON metadata) used in
blockchain-based projects such as NFTs, tokens, and collections.

All assets are intended to be referenced via public, stable URLs
(e.g. GitHub raw, IPFS, Arweave) and may already be used on-chain.

---

## Repository Structure

images/   - Image assets (PNG/JPG) used by tokens and NFTs  
json/     - JSON metadata files referencing image assets  
scripts/  - Helper scripts for asset generation and automation

Assets are organized by category (e.g. dog, cat, wow) to support
multiple collections and long-term scalability.

---

## Legacy Assets

Some files exist at the repository root level.
These assets are already referenced by on-chain metadata and must not be removed,
renamed, or relocated.

They are preserved strictly for backward compatibility.

---

## Usage

Typical asset usage flow:

1. Image is stored in the images/ directory
2. JSON metadata references the image via a public URL
3. Blockchain programs or minting scripts reference the JSON metadata URI

Example public asset URL:

https://raw.githubusercontent.com/AleksandarSourceCode/dev-assets/main/images/dog/happy-dog.png

---

## Important Notes

- Do not modify or delete assets that are already used on-chain
- New assets should be added only inside category folders
- Treat this repository as read-only after assets are minted

---

Author: Aleksandar Joksić
