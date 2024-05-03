## MPT Proof Generator
This directory contains a rust program that generates random but valid MPT proofs. The generated files can then be used for testing the MPT implementation on a large dataset.

To generate a new set of testing files, run the following command:
```bash 
cargo run
```

It is required to expose a `RPC_URL_MAINNET=<rpc_url>` environment variable for fetching the proofs.