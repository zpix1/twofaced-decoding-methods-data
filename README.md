# Error-correcting codes without parity-check bits

The [Python results](data/tf-mle-grid-256x2048.csv) use `SeedSequence([2026110502, int(is_bsc), p_index, block_index])` as seed. Within each block, all `l` and `pi` values share source bits and channel draws.

The [C++ results](data/tf-mle-grid-256x2048-additional.csv) use the same CSV columns.

| BEC | BSC |
| :---: | :---: |
| ![BEC results](figures/tf-mle-bec-256x2048.png) | ![BSC results](figures/tf-mle-bsc-256x2048.png) |
