# mycelium-std-vsa-myc

Mycelium-language sibling of [`tzervas/mycelium-std-vsa`](https://github.com/tzervas/mycelium-std-vsa).

| Field | Value |
|---|---|
| **Program** | PROGRAM-SELFHOST-DECOMPOSE Phase T |
| **Rust twin** | tzervas/mycelium-std-vsa |
| **Transpile tip** | monorepo `3277b99618c858f03b1f482ed9ae15e10b9c3909` (post G-β when available) |
| **Archive provenance** | monorepo main `aad96b7a425710db5e91094d4fc2ca21a129e41a` |
| **Honesty** | Emissions are **Declared/Empirical** gap-profiler output until differential-witnessed port (M-993). Not production-ready DN-88 §3. |

## Layout

- `lib/` — `.myc` nodules (transpile + optional hand-port seed)
- `experiments/vet/` — gap profiles + vet artifacts

## Check

When `myc-check` is available:

```bash
myc check lib/*.myc
```
