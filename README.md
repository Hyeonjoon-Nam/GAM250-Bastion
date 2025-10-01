# They Are & Bastion (Custom C++)

This repository contains **two projects in one history**:

- **They Are (Sep–Dec 2023)** — Top-down defense with massively optimized **A\*** via a **singleton path manager**.  
  👉 Code snapshot: [`they-are-1.0`](https://github.com/Hyeonjoon-Nam/GAM250-Bastion/tree/they-are-1.0)

- **Bastion (Mar–Jun 2024)** — Loop-route defense with **data-driven merge** and **state-based transitions**, plus **text-file parsing** for iteration speed.  
  👉 Current code: [`main`](https://github.com/Hyeonjoon-Nam/GAM250-Bastion/tree/main)

---

## They Are — Summary
**Impact:** Replaced per-frame per-agent A\* with a **singleton path manager**, reducing pathfinding cost by **99.9%+**.  
**Highlights:** Wave/Map systems, diverse enemy patterns, **text-file parsing** for balancing.  
**Benchmarks:** Reduced runtime by **~5,900×** (100 monsters × 240 frames) up to 25,000× faster in stress tests.  
➡ Full logs: [`benchmarks/bench_results.txt`](./benchmarks/bench_results.txt)

## Bastion — Summary
**Impact:** Refactored fragile merge logic into **data-driven mappings + state-based transitions**; externalized **wave/enemy/unit stats** via **text-file parsing** → faster iteration & fewer bugs.

## Build / Run
- Visual Studio 2019+ (C++17), x64 Debug/Release
- Run from project root (adjust working directory if needed)

> This repository mirrors our DigiPen project history for portfolio purposes.  
> School-proprietary frameworks/assets are excluded where necessary.  
> Credits to all teammates; see commit history for contributors.
