# Build instructions

The website is built using [Zola](https://www.getzola.org/). To build the
website, first clone the repository and initialize the submodules:

```bash
    git submodule update --init --recursive
```

Zola can be installed using `cargo` directly using the following command:

```bash
    cargo install --path 3rd-party/zola --locked
```

# Deploying

The website can be previewed with `zola serve`, and build with `zola build`.