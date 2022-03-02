#Script build

## intro
build script that convert ts/js file to es & commonjs module
## Usage

add  `cafune-build [options]` script to `package.json`

**Options**:
| short param | full param |description | default |
| :--: | :--: | -- | -- |
| -c | --config <type> | babel config file path | **./babel.config.js** |
| -s | --src <type> | src path to compile |  **./src** |
| -e | --es <type> | es path to output compiled es module file | **./es** |
| -l | --lib <type> | lib path to output compiled commonjs module file |  **./lib** |
| -h | --help | display help for command |  |
