# ntfs-rw

An NTFS filesystem implementation in pure Rust, aiming for read and write support.

> **Status: early development.** Nothing is usable yet, and the API will change without notice.

## Goals

- **Read and write NTFS volumes** without depending on any C library.
- **A `no_std` core**, so the library can run outside desktop operating systems.

## Crates

| Crate | Path | Description |
|---|---|---|
| `ntfs-rw` | [`crates/core`](crates/core) | The library |
| `ntfs-rw-cli` | [`crates/cli`](crates/cli) | Command-line tool for inspecting and working with NTFS volumes and disk images |

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT License ([LICENSE-MIT](LICENSE-MIT))

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in this work, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
