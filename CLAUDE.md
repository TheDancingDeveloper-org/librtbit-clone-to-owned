# librtbit-clone-to-owned

Util traits to represent something that can be made owned and change type at the same time.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |
| librtbit-buffers (lib) | git | v0.1.0 |
| librtbit-bencode (lib) | git | v0.1.0 |
| librtbit-core (lib) | git | v0.1.0 |
| librtbit-peer-protocol (lib) | git | v0.1.0 |
| librtbit-dht (lib) | git | v0.1.0 |

### Depends On

- **bytes** (crates.io, v1) — for Bytes type in CloneToOwned trait

## Public API

- `CloneToOwned` trait — recursive type-level owned/borrowed conversion
- Implementations for `Option<T>`, `Vec<T>`, `HashMap<K,V>`, `BTreeMap<K,V>`, `u8`, `u32`
