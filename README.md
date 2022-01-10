# figma-tokens-example-multi

This repo contains Figma Tokens (with GitHub sync enabled) to be automatically transformed with token-transformer and Style Dictionary in a dark/light theme environment.

Tokens are defined in `tokens.json` and can be edited either directly or with the Figma Tokens plugin in Figma. The GitHub action will automatically generate tokens to the `tokens/` directory that can then be read by Style Dictionary, which will output tokens to the format you defined in `build.js` - css variables will be generated in the `output` directory.
