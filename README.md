# saves24

Hobbyist developer. I write Rust and Python, and I like software that runs
without a cloud account.

## portalis

An offline, hash-locked package manager with a Nix-style store. Build a package
or import an archive, keep every version in its own store directory, activate it
by link, roll back by generation. Ships as a static musl binary; releases carry
SHA-256 sums and an Ed25519 signature.

→ [github.com/saves24/portalis](https://github.com/saves24/portalis)

## What I care about

- **Offline by default.** No account, no telemetry, no network call you did not ask for.
- **Reproducible builds.** Locked dependencies, hashed inputs, a build that fails loudly.
- **Small tools.** One binary, one config file, tests that run on a clean machine.
