# Prerequisites

## Needed packages
```bash
sudo apt update
sudo apt install libwebkit2gtk-4.0-dev \
    build-essential \
    curl \
    wget \
    libssl-dev \
    libgtk-3-dev \
    libayatana-appindicator3-dev \
    librsvg2-dev
```
## Install Rust
```curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh```



# How to reproduce bug

```bash
cargo run --example bug
```

Then press Login with SAML SSO

enter a valid account (etc mine: martin.myhrman@volvocars.com)

check network tab in dev console.
