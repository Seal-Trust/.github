# SealTrust

**Cryptographic Verification & Encrypted Storage for AI Training Datasets**

Built on Sui | Walrus | Seal | Nautilus TEE

---

## What We Do

SealTrust provides end-to-end verification and secure storage for AI training datasets. We ensure data integrity and controlled access through a decentralized pipeline:

1. **Hash** - Generate cryptographic hash of unencrypted dataset for integrity verification
2. **Encrypt** - Secure data with Seal's threshold encryption
3. **Upload** - Store encrypted data on Walrus decentralized storage
4. **Verify** - Validate metadata through Nautilus TEE hardware attestation
5. **Record** - Mint DatasetNFT on Sui blockchain as immutable proof
6. **Access** - Authorized users decrypt with session keys

## Repositories

| Repository | Description |
|------------|-------------|
| [sealtrust-frontend](https://github.com/Seal-Trust/sealtrust-frontend) | Next.js web application |
| [sealtrust-contracts](https://github.com/Seal-Trust/sealtrust-contracts) | Sui Move smart contracts |
| [sealtrust-enclave](https://github.com/Seal-Trust/sealtrust-enclave) | Nautilus TEE verification service |

## Tech Stack

- **Sui** - Layer 1 blockchain for DatasetNFT records
- **Walrus** - Decentralized blob storage for encrypted datasets
- **Seal** - Threshold encryption with on-chain access control
- **Nautilus** - AWS Nitro Enclave for hardware-attested verification

## Links

- Website: [sealtrust.app](https://sealtrust.app)
- Documentation: Coming soon

---

<p align="center">
  <strong>Verify. Encrypt. Trust.</strong>
</p>
