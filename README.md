# Carpinchos BCH Argentina — Part 2

Artwork and metadata for **2,500 pieces**, numbered **2501–5000**, from a collection of **5,000 unique NFTs**.

A project by [BCH Argentina](https://www.bcharg.com/). Official account: [bchargentina](https://github.com/bchargentina).

## Status

The artwork is complete. **The tokens have not been issued, and sales are not open.** The official Category ID, authenticated BCMR, and purchase link will be published after issuance testing.

Planned price: **0.075 BCH per NFT**, across three rounds of **2,000, 1,500, and 1,500**. The suggested interval is 6–8 weeks, subject to sales and demand. No launch date has been set.

## Files

- `images/`: final 1254×1254 WebP images, quality 95.
- `metadata/`: names, descriptions, attributes, and image URLs pinned to the artwork commit.
- `SHA256SUMS`: SHA-256 image hashes.
- `manifest.json`: IDs, composition records, file sizes, and hashes. Original asset identifiers are retained for reproducibility.
- `collection.json`: collection configuration and status.
- [BENEFITS.md](BENEFITS.md): Club membership credit, ARG Tokens airdrops, and support for BCH adoption.
- [LICENSE.md](LICENSE.md): NFT holder image usage license.
- [validacion-unicidad.json](validacion-unicidad.json): uniqueness validation results for the entire 5,000-piece collection.

The individual JSON files do not replace the CashTokens BCMR. Splitting the artwork across two repositories is for storage only; it does not represent separate collections or sale rounds.

## Integrity

Artwork commit: `b5ba20ba843bd0798dbed7e66647b1793e4d9643`. All 5,000 final files were checked: no duplicate combinations or images, including comparison of decoded pixels.

Verify this part on Linux:

```sh
sha256sum -c SHA256SUMS
```

On macOS: `shasum -a 256 -c SHA256SUMS`.

Other part: [carpinchos-nft-01](https://github.com/bchargentina/carpinchos-nft-01).
