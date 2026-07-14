# Setup WebAssembly Binary Toolkit

## Example
```yaml
- uses: BlackAsLight/setup-wabt@v2.0.0
  env:
    GH_TOKEN: ${{ github.token }}
  with:
    # Version can be one of:
    # - "canary": Clones the WABT repo and builds from source.
    # - "latest": (Default) Downloads the latest release binaries from GitHub Releases.
    # - A specific release tag (e.g., "1.0.36"): downloads that exact version's binaries.
    version: 1.0.36
```
