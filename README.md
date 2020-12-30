# lsquic-static-alpine

[LSQUIC](https://github.com/litespeedtech/lsquic) static library compiled on Alpine Linux.

`liblsquic.a` is licensed under `LICENSE.lsquic` and `LICENSE.chrome`.

LSQUIC uses [BoringSSL](https://github.com/google/boringssl), which is licensed under `LICENSE.boringssl`.

## Updating

1. Update the commit IDs in `env.sh`
2. Make a PR and test with the CI artifact
3. Merge the PR to automatically create a new release
