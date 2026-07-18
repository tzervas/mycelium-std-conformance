# CROSS-REF — mycelium-std-conformance

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-cert | https://github.com/tzervas/mycelium-runtime | `ab9cee665b620ed80ab74ea61ea639817dc49077` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-cert` (see monorepo `docs/api-index/INDEX.md#mycelium-cert`) |
| mycelium-core | https://github.com/tzervas/mycelium-core | `781d3fcceba82acfe6b0eb46650513bd78a2416b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-core` (see monorepo `docs/api-index/INDEX.md#mycelium-core`) |
| mycelium-interp | https://github.com/tzervas/mycelium-runtime | `ab9cee665b620ed80ab74ea61ea639817dc49077` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-interp` (see monorepo `docs/api-index/INDEX.md#mycelium-interp`) |
| mycelium-l1 | https://github.com/tzervas/mycelium-l1 | `cd32a1ed7ab7d2be38c9c3047da7318d182b7a1c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-l1` (see monorepo `docs/api-index/INDEX.md#mycelium-l1`) |
| mycelium-mlir | https://github.com/tzervas/mycelium-codegen | `f144d635e970257aee5b618f8cdfaa736e2c391d` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-mlir` (see monorepo `docs/api-index/INDEX.md#mycelium-mlir`) |
| mycelium-std-content | https://github.com/tzervas/mycelium-std-content | `792eb7fe476ebf50bae1d8a20e3a7fba83a16d8b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-content` (see monorepo `docs/api-index/INDEX.md#mycelium-std-content`) |
| mycelium-std-core | https://github.com/tzervas/mycelium-std-core | `580b64316774e22f0b7d5d495ca1d9b9d6536a60` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-core` (see monorepo `docs/api-index/INDEX.md#mycelium-std-core`) |
| mycelium-std-diag | https://github.com/tzervas/mycelium-std-diag | `b964be31c657a81e6b2197c8ba7ede1f01ac2cd3` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-diag` (see monorepo `docs/api-index/INDEX.md#mycelium-std-diag`) |
| mycelium-std-error | https://github.com/tzervas/mycelium-std-error | `42ae6b191bf92601aa8a5cceba26a2035d6f5542` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-error` (see monorepo `docs/api-index/INDEX.md#mycelium-std-error`) |
| mycelium-std-numerics | https://github.com/tzervas/mycelium-std-numerics | `cdfb2cdef08818091d47ec99f592947c1ccc4085` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-numerics` (see monorepo `docs/api-index/INDEX.md#mycelium-std-numerics`) |
| mycelium-std-recover | https://github.com/tzervas/mycelium-std-recover | `cc89777915a31e9ce9e8676a978a185eed467590` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-recover` (see monorepo `docs/api-index/INDEX.md#mycelium-std-recover`) |
| mycelium-std-select | https://github.com/tzervas/mycelium-std-select | `a082e7ff280c8ed1fcfc3e0d57e7020d39a17257` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-select` (see monorepo `docs/api-index/INDEX.md#mycelium-std-select`) |
| mycelium-std-spore | https://github.com/tzervas/mycelium-std-spore | `153581f234ddf2643ab2fb4e329086b4e128fc44` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-spore` (see monorepo `docs/api-index/INDEX.md#mycelium-std-spore`) |
| mycelium-std-swap | https://github.com/tzervas/mycelium-std-swap | `af04ae6ce366b883c8c56d266d19342f447c3ac3` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-swap` (see monorepo `docs/api-index/INDEX.md#mycelium-std-swap`) |
| mycelium-std-ternary | https://github.com/tzervas/mycelium-std-ternary | `523ce084d85e2f84aef3b645c36bde4df9ec613c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-ternary` (see monorepo `docs/api-index/INDEX.md#mycelium-std-ternary`) |
| mycelium-std-testing | https://github.com/tzervas/mycelium-std-testing | `b67755101f65071b81ad965896406107a88e370c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-testing` (see monorepo `docs/api-index/INDEX.md#mycelium-std-testing`) |
| mycelium-std-time | https://github.com/tzervas/mycelium-std-time | `fedd18411bf33cc2cd2b0d7ba41e1259719d23c0` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-time` (see monorepo `docs/api-index/INDEX.md#mycelium-std-time`) |

**Owning docs:** `docs/spec/stdlib/conformance.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
