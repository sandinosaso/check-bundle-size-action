# Check Bundle Size javascript action

This action check for the size of the bundle

## Inputs

### `github_token`

**Required** The name of the person to greet. Default `"World"`.

### `command_for_building`

**Required** The command for building. Default `"yarn build"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/check-bundle-size@v1
with:
  github_token: XYZ
  command_for_building: 'yarn build'