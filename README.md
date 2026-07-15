# Setup WebAssembly Binary Toolkit

## Example

```yaml
- uses: BlackAsLight/setup-wabt@v2.1.0
  env:
    GH_TOKEN: ${{ github.token }}
  with:
    # Version can be one of:
    # - "latest" (default): Download the latest GitHub Release binaries.
    # - "canary": Build WABT from the latest source.
    # - A specific release tag (for example, "1.0.36"): Download that release's binaries.
    version: 1.0.36

    # Whether to save time by using actions/cache. Defaults to true.
    cache: true
```
