# tippecanoe-action

GitHub Action to install [tippecanoe](https://github.com/felt/tippecanoe) into your workflow's environment.

## Supported Platforms

| OS    | Architecture          | Runner             |
|-------|-----------------------|--------------------|
| Linux | x64 (Intel/AMD)       | `ubuntu-latest`    |
| Linux | arm64 (ARM)           | `ubuntu-24.04-arm` |
| macOS | x64 (Intel)           | `macos-13`         |
| macOS | arm64 (Apple Silicon) | `macos-latest`     |

The action automatically detects your runner's OS and architecture.

## Usage

```yaml
- uses: michaelkreil/tippecanoe-action@main
```

## Example

```yaml
jobs:
  build-tiles:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: michaelkreil/tippecanoe-action@main
      - run: tippecanoe -o output.mbtiles input.geojson
```
