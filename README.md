

config.json
```json
    {
      "output_path": "../path/to/builds",
      "public_path": "/public/uri/prefix",
      "entry": {
        "polyfills": "./src/polyfills.browser.ts",
        "homepage":  "./src/homepage.browser.ts"
      }
    }
```

Aliases
=======
Define aliases in both files - tsconfig.json(compilerOptions.paths) and config/webpack.common.js (resolve.alias)

