# nixpkg-burrow

Nix packaging scaffold for `@os-eco/burrow-cli` (OS-isolated sandbox runtime for coding agents).

## Outputs

- `default` (`out`): `burrow` (long-form binary)
- `bw`: `bw` (short-form alias binary)

## Local use

From this checkout, run `nix run . -- --help`, or install with
`nix profile install .`.
