# T3 Sovereign runtime distribution

This repository contains only generated public installation metadata and signed
runtime release assets for the private sovereign T3 deployment.

The canonical installer will be available at:

```sh
curl -fsSL https://get.moondiner.com/install | sh -s -- serve
```

Runtime archives are untrusted until the installer verifies their Ed25519
manifest signature, exact version, platform, compressed size, and SHA-256.

Do not commit source code, credentials, private signing keys, or infrastructure
configuration to this repository. Sovereign CI owns generated release content.
