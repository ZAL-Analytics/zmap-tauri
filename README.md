# zmap-tauri

**A simulation-grade interactive map engine for Tauri desktop apps.**

`zmap-tauri` is a Rust library built on top of [Tauri](https://tauri.app) that bridges the gap between a static map display and a fully interactive simulation canvas. It pairs with a Svelte frontend to deliver animated, data-driven maps suited for desktop simulation software, monitoring dashboards, and logistics tooling.

> **Status:** Early development, crate name reserved. Public API coming soon.

---

## Why zmap-tauri?

Most map libraries stop at pins and polylines. `zmap-tauri` is designed for use cases where the map itself is a live, interactive simulation surface:

- **Moving objects**, vehicles, agents, or assets that travel paths with smooth animation
- **Interactive overlays**, tooltips with embedded Svelte components: buttons, sliders, dropdowns, live charts
- **Dynamic visual styles**, per-element color rules, glow effects, blinking states, particle trails, heatmaps
- **Borders and regions**, highlight, pulse, or animate map regions based on live data
- **Event-driven updates**, the Tauri command layer pushes state changes directly to map elements without full re-renders
- **Simulation time control**, built-in hooks for play/pause/scrub for replay and prediction workflows

---

## Planned Features

| Feature | Status |
|---|---|
| Moving entity animation | Planned |
| Custom Svelte tooltip components | Planned |
| Particle effects on map elements | Planned |
| Dynamic color & pattern rules | Planned |
| Region highlighting & pulsing | Planned |
| Tauri command bridge (Rust ↔ Svelte) | Planned |
| Layer management (toggle, z-order) | Planned |
| Time-step / replay support | Planned |

---

## Target Stack

- **Backend:** Rust + Tauri v2
- **Frontend:** Svelte 5
- **Map renderer:** TBD (Leaflet / MapLibre GL / custom canvas)

---

## License

Licensed under the [Apache License 2.0](LICENSE).
