# OZI Draft

OZI Python project release draft action

## Inputs

* github-token - defaults to current token
* checkout-submodules - checkout submodules as well. true, false, or recursive (default: true)

## Outputs

* drafted - a release has been drafted
* tag - release tag name

## Permissions
Requires the following:
```yaml
    permissions:
      contents: write
      id-token: write
```
## License

MIT No Attribution

