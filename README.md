# Homebrew tap for VaultKey

[VaultKey](https://github.com/dhruvkulkarni02/vaultkey) is a local, offline password manager for the terminal, with Argon2id key derivation and AES-256-GCM encryption.

## Install

```bash
brew install dhruvkulkarni02/vaultkey/vaultkey
```

This taps the repository and installs the `vk` and `vaultkey` commands. Then create a vault:

```bash
vk init
```

Upgrade with `brew upgrade vaultkey`. See the [VaultKey README](https://github.com/dhruvkulkarni02/vaultkey#readme) for usage.

## Platforms

| Platform | Install |
|----------|---------|
| macOS on Apple Silicon | Prebuilt bottle, installs in seconds |
| Linux (x86_64) | Prebuilt bottle |
| macOS on Intel | Builds from source, including Rust and Python, because Homebrew no longer ships Intel bottles for them. Installing with `pip` is much faster; see the VaultKey README. |

## Maintenance

Each formula update goes through a pull request. `brew test-bot` builds, tests and bottles it on Linux and Apple Silicon macOS. Adding the `pr-pull` label publishes the bottles and merges the update.
