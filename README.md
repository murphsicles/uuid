# @std/uuid — UUID Generation for Zeta

Auto-converted from [uuid](https://crates.io/crates/uuid) v1.23.1 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **v4** — random UUIDs (via `@crypto/rand`)
- **v7** — Unix timestamp-based UUIDs (time-ordered, DB-friendly)
- **v1/v6/v8** — additional UUID versions for compatibility
- **serde** — serialize/deserialize with `@data/serde`
- **fmt** — hyphenated, urn, simple formatting
- **parse** — strict and lenient UUID string parsing

## Usage
```zeta
use @std/uuid::Uuid;

let id = Uuid::new_v4();
println!("{}", id.hyphenated());
```

## Stats: ~3,922 lines across 23 source files, 0 unsupported items

## License
MIT