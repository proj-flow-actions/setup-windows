# Setup Windows
Prepare C++ tools specific for Windows

## Inputs

|Input|Description|Default value|
|-|-|-|
|`install-occ`|Should this action install OpenCppCoverage||
|`install-folder`|The designated install folder for OpenCppCoverage|`"C:\Program Files (x86)"`|
|`install-nsis`|Version of NSIS to install, or false to skip installation||

## Example usage

```yaml
uses: proj-flow-actions/setup-windows@v1.1
with:
  install-nsis: '3.10'
```
