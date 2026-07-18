# CROSS-REF — mycelium-std-conformance

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-cert | https://github.com/tzervas/mycelium-runtime | `487b1e7049ff521b1a6fa33f376245089e7dc1e1` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-cert` (see monorepo `docs/api-index/INDEX.md#mycelium-cert`) |
| mycelium-core | https://github.com/tzervas/mycelium-core | `46d2515cbd86d2ae4d1365f4adcd2796737e9f0b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-core` (see monorepo `docs/api-index/INDEX.md#mycelium-core`) |
| mycelium-interp | https://github.com/tzervas/mycelium-runtime | `487b1e7049ff521b1a6fa33f376245089e7dc1e1` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-interp` (see monorepo `docs/api-index/INDEX.md#mycelium-interp`) |
| mycelium-l1 | https://github.com/tzervas/mycelium-l1 | `2b92f54349eb0d4f67e32e983874df76908b9ab6` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-l1` (see monorepo `docs/api-index/INDEX.md#mycelium-l1`) |
| mycelium-mlir | https://github.com/tzervas/mycelium-codegen | `505448cbfb5553a34aca726f0d1b884981a83631` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-mlir` (see monorepo `docs/api-index/INDEX.md#mycelium-mlir`) |
| mycelium-std-content | https://github.com/tzervas/mycelium-std-content | `a6059bae85256fed1272f38a8cbbd2dec2e8c56c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-content` (see monorepo `docs/api-index/INDEX.md#mycelium-std-content`) |
| mycelium-std-core | https://github.com/tzervas/mycelium-std-core | `376762cc17853e1582684ececf9e760426bcfb0c` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-core` (see monorepo `docs/api-index/INDEX.md#mycelium-std-core`) |
| mycelium-std-diag | https://github.com/tzervas/mycelium-std-diag | `0ce2e431a4786ec5f974fc66e774cb0a9b77def4` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-diag` (see monorepo `docs/api-index/INDEX.md#mycelium-std-diag`) |
| mycelium-std-error | https://github.com/tzervas/mycelium-std-error | `dece7d3b1ce12df65cfba0131d151689f1e42a5e` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-error` (see monorepo `docs/api-index/INDEX.md#mycelium-std-error`) |
| mycelium-std-numerics | https://github.com/tzervas/mycelium-std-numerics | `2676276b1559f0c1c0b1c0c39ad48ba6ff89d639` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-numerics` (see monorepo `docs/api-index/INDEX.md#mycelium-std-numerics`) |
| mycelium-std-recover | https://github.com/tzervas/mycelium-std-recover | `ad8787428c0d8c1eb2bf3a8cd6504cc39bca00bf` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-recover` (see monorepo `docs/api-index/INDEX.md#mycelium-std-recover`) |
| mycelium-std-select | https://github.com/tzervas/mycelium-std-select | `a800a36061be6177ed4885707bf5d0f5e125ed73` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-select` (see monorepo `docs/api-index/INDEX.md#mycelium-std-select`) |
| mycelium-std-spore | https://github.com/tzervas/mycelium-std-spore | `29cbddd0a1480c6b784805bb8d7e5141497d7dc0` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-spore` (see monorepo `docs/api-index/INDEX.md#mycelium-std-spore`) |
| mycelium-std-swap | https://github.com/tzervas/mycelium-std-swap | `55bb071af6b428c933c17c7cd8045f8c8663e5ea` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-swap` (see monorepo `docs/api-index/INDEX.md#mycelium-std-swap`) |
| mycelium-std-ternary | https://github.com/tzervas/mycelium-std-ternary | `bcc63ee0fcd9e07ae1d9cc85241e251767a6d8bf` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-ternary` (see monorepo `docs/api-index/INDEX.md#mycelium-std-ternary`) |
| mycelium-std-testing | https://github.com/tzervas/mycelium-std-testing | `6f3a51aa61a60b508fa6a8a15cb7b12e4b736413` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-testing` (see monorepo `docs/api-index/INDEX.md#mycelium-std-testing`) |
| mycelium-std-time | https://github.com/tzervas/mycelium-std-time | `47ef9e7ec4143c97878083ca5c15930a21eeed83` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-std-time` (see monorepo `docs/api-index/INDEX.md#mycelium-std-time`) |

**Owning docs:** `docs/spec/stdlib/conformance.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
