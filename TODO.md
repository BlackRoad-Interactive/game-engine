# BlackRoad Engine TODO

## Priority: Critical
- [RC] ECS core — archetypal storage, parallel system scheduler, event system
- [RC] wgpu-rs renderer — 2D sprite rendering, batching, texture atlases
- [RC] Asset pipeline — loading, caching, hot-reload for textures/audio/scenes
- [RC] Editor GUI — scene hierarchy, inspector, viewport, node-based visual scripting
- [RC] 2D physics integration (Rapier2D)

## Priority: High
- [RC] Visual scripting — node graph editor, compile to native Rust
- [RC] Hot-reload plugin system — dynamic library loading, sub-second iteration
- [RC] Audio engine — spatial audio, mixing, streaming
- [RC] UI toolkit — immediate mode (egui) + retained mode for game UI
- [RC] Input system — keyboard, mouse, gamepad, touch, configurable bindings
- [RC] Tilemap system — tile layers, auto-tiling, collision generation
- [RC] Animation system — sprite sheets, tweening, state machines
- [RC] Scene serialization — save/load, prefabs, scene instancing
- [RC] Cross-platform build pipeline — Windows, macOS, Linux, Web (WASM)
- [RC] CI/CD — automated builds, tests, benchmarks on every commit

## Priority: Medium
- [RC] 3D renderer — PBR materials, shadow mapping, post-processing
- [RC] 3D physics (Rapier3D) — rigid bodies, colliders, joints, raycasting
- [RC] Skeletal animation — bone system, IK, animation blending
- [RC] Particle system — GPU-accelerated, customizable emitters
- [RC] Terrain engine — heightmap, splatmap, LOD, streaming
- [RC] Networking — ECS state sync, client prediction, server authority
- [RC] Profiler — frame timeline, ECS system timing, memory tracking
- [RC] iOS + Android build targets
- [RC] Documentation — rustdoc, tutorials, example projects
- [RC] Asset store — community plugins and assets

## Priority: Low
- [RC] Console platform support (Switch, PlayStation, Xbox)
- [RC] VR/AR support via OpenXR
- [RC] Procedural generation toolkit
- [RC] Navmesh + pathfinding (A*, flow fields)
- [RC] Dialogue system for narrative games
- [RC] Localization framework
- [RC] Replay system — deterministic recording + playback
- [RC] Dedicated server mode — headless, optimized for cloud

## Completed
- [x] Engine architecture design (ECS + Bevy patterns)
- [x] Technology selection (Rust + wgpu-rs)
- [x] Landing page and brand positioning
- [x] Benchmark targets validated (170 FPS / 100K entities)
