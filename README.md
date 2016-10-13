# webapp

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

### Fixes/Changes

**1: Issue**:
Running "cssmin:generated" (cssmin) task
Warning: Path must be a string. Received undefined Use --force to continue.
_Fix_:
Updating grunt-contrib-cssmin dependency version on package.json:
From: "grunt-contrib-cssmin": `"^0.12.0"
To: "grunt-contrib-cssmin":  "^1.0.2"



