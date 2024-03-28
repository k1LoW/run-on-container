# run-on-container

Action to run a command on any container on any platform.

## Usage

### Run on ubuntu:latest + linux/arm64

``` yaml
- uses: k1LoW/run-on-container@main
  with:
    run: |
      uname -a
    image: ubuntu:latest
    platform: linux/arm64
```

