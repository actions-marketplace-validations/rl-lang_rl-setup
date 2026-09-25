# rl-setup

Installs RL prebuilt binaries. No Rust toolchain needed.

```yaml
- uses: rl-lang/rl-setup@main
  with:
    version: latest    # latest | nightly | vX.Y.Z
    binaries: rl       # comma-separated, or all
```

| Input | Default |
|---|---|
| `version` | `latest` |
| `binaries` | `all` |

Outputs `install-dir` and `version`. Other `rl-lang/rl-*` actions call this first — use it directly when your own `run:` steps need `rl`.
