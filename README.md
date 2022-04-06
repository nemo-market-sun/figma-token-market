# figma-tokens-example

This example illustrates how you can transform your tokens stored on Figma Tokens (with GitHub sync enabled) to be automatically transformed with token-transformer and Style Dictionary.

Change your tokens in `tokens.json` (either directly or with the Figma Tokens plugin in Figma). The GitHub action will automatically generate tokens to the `tokens/` directory that can then be read by Style Dictionary, which will output tokens to the format you defined in `config.json`


https://cdn.jsdelivr.net/gh/nemo-market/figma-token-market/css/variables.css

'''
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/gh/nemo-market/figma-token-market/css/variables.css"
  />
'''
