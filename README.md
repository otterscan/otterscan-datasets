# Otterscan Datasets

This repo contains some raw datasets produced by Otterscan indexers.

Since the file sizes are big, we'll not share them using GitHub, but instead this repo will contain up-to-date magnet links.

## Mainnet data

> Please help seed the files!

### Up to block 16,950,000 (388 MB compressed `.tar.zst`)

Magnet link (copy/paste it in your favorite torrent client; unpack the tarball with zstd):

`magnet:?xt=urn:btih:74bd99a5de7a473446112a5bc38ca1a072fd7021&dn=otterscan-datasets-mainnet-16950000.tar.zst&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fopentracker.i2p.rocks%3A6969%2Fannounce&tr=https%3A%2F%2Fopentracker.i2p.rocks%3A443%2Fannounce&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A6969%2Fannounce`

Contains:

- ERC20: block number, contract address, name, symbol, decimals
- ERC165: block number, contract address
- ERC721: block number, contract address, name, symbol
- ERC1155: block number, contract address
- ERC1167: block number, contract address, logical contract address
- ERC4626: block number, contract address, name, symbol, decimals, asset contract address

## License

[MIT](./LICENSE).
