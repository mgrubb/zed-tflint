# Zed tflint

A [Zed](https://zed.dev/) extension for running tflint on your Terraform codebase.

## Requirements
- [tflint](https://github.com/terraform-linters/tflint)

## Configuration
*Only needed to override the default command line arguments.*
```json
{
  "lsp": {
    "tflint": {
      "initialization_options": {
        "command": [
          "tflint",
          "--langserver"
        ]
      }
  }
}
```
