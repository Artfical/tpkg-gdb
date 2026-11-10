# gdb

GDB 17.2: the GNU debugger (breakpoints, stepping, backtraces, registers and memory; needs ptrace)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install gdb
```

| | |
|---|---|
| Version | 17.2 |
| Licence | GPL-3.0-or-later |
| Upstream | https://www.sourceware.org/gdb/ |
| Needs | [`busybox`](https://github.com/Artfical/tpkg-busybox) |
| Needs tOS build | 627 or newer |
| Size | 5150812 bytes (12325327 unpacked) |
| SHA-256 of the `.tpkg` | `b3d469c89dfa75e1d72c874134ff10d95a340fdb49929783814e6d8675c34c88` |

## Commands it adds

| Command | Runs |
|---|---|
| `gdb` | `bin/gdb-tos` |

## Download

The package file (`gdb-17.2.tpkg`) and the sources it was built from are the assets of the
[v17.2 release](https://github.com/Artfical/tpkg-gdb/releases/tag/v17.2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `gdb-17.2.tar.xz`

Check a download: `sha256sum gdb-17.2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
