# biogeometric_site

## Install Hugo

If you are using MacOS, directly
```
brew install hugo
```

Or Windows, following tutorial in https://gohugo.io/getting-started/installing.

## Preview

Stay in top directory and type:
```
hugo server -D
```

And go to `http://localhost:1313/` in your browser. Done.

## Tree architecture

- The global settings (for Home page), go to `./config.toml`, such as header, tagline, descriptions.
- To change media elements displayed, go to `./static/`.
- To edit documents, go to `./content/`, grouped by column name in header.

