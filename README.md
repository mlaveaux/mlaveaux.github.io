# Build instructions

Acquire `zola` using the installation instructions provided on [getzola.org](https://www.getzola.org/documentation/getting-started/installation/). Alternatively, since Rust is a prerequired for building the website anyway we provide the sources in `3rd-party/zola`. From there it can be installed using `cargo` directly using the following command:

```
    cargo install --path zola --locked
```

# Deploying

The website can be previewed with `zola serve`, and build with `zola build`.