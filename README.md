# LTFS Build docker action for Ubuntu 18.04 (Bionic)

This action builds the LTFS package on Ubuntu 18.04

## Inputs

### `destination`

**Required** Destination of install。 Default is `/tmp/ltfs`。

## Outputs

None

## Usage

```
uses: LinearTapeFileSystem/Ubuntu1804-Build@v1.0
with:
  destination: '/tmp/ltfs'
```
