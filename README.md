# Setup WebAssembly Binary Toolkit

## Example
```yaml
- uses: BlackAsLight/setup-wabt@v1.1.1
  env:
    GH_TOKEN: ${{ github.token }}
  with:
    # Version can be one of:
    # - "canary": Clones the WABT repo and builds from source (Linux/macOS). On Windows, behaves like "latest" (downloads binaries).
    # - "latest": (Default) Downloads the latest release binaries from GitHub Releases.
    # - A specific release tag (e.g., "1.0.37"): downloads that exact version's binaries.
    version: latest
```
