# BlackRoad Engine Roadmap

## Phase 1: 2D Foundation (Months 1-6)
- [RC] ECS core — archetypal storage, parallel scheduler, events, resources
- [RC] wgpu-rs 2D renderer — sprites, batching, texture atlases, cameras
- [RC] Asset pipeline — async loading, caching, hot-reload
- [RC] 2D physics — Rapier2D integration, colliders, rigid bodies
- [RC] Audio engine — basic playback, spatial audio, mixing
- [RC] Input system — keyboard, mouse, gamepad, touch
- [RC] Tilemap system — layers, auto-tiling, collision gen
- [RC] Sprite animation — sheets, tweening, state machines
- [RC] UI toolkit — egui integration for editor + game UI
- [RC] Editor GUI v1 — scene hierarchy, inspector, viewport
- [RC] Scene serialization — save/load, prefabs
- [RC] Cross-platform — Windows, macOS, Linux, Web (WASM)
- **Milestone**: Ship 2D games to all desktop + web platforms

## Phase 2: Visual Scripting + Polish (Months 7-9)
- [RC] Visual scripting — node graph editor, Rust compilation
- [RC] Hot-reload plugin system — dynamic library loading
- [RC] Editor GUI v2 — visual script editor, asset browser, console
- [RC] Profiler — frame timeline, system timing, memory
- [RC] iOS + Android build targets
- [RC] Documentation — rustdoc, tutorials, 10 example projects
- [RC] CI/CD templates for game studios
- [RC] Community site + forums
- **Milestone**: Visual scripting MVP, mobile targets, public beta

## Phase 3: 3D Engine (Months 10-14)
- [RC] 3D renderer — PBR, shadow mapping, post-processing pipeline
- [RC] 3D physics — Rapier3D, rigid bodies, joints, raycasting
- [RC] Skeletal animation — bones, IK, blend trees
- [RC] Particle system — GPU-accelerated emitters
- [RC] Terrain engine — heightmap, splatmap, LOD
- [RC] Navmesh + pathfinding — A*, flow fields
- [RC] Advanced lighting — GI probes, reflection probes, SSAO
- **Milestone**: Production-ready 3D engine

## Phase 4: Multiplayer + Ecosystem (Months 15-18)
- [RC] Networking — ECS state sync, client prediction, server authority
- [RC] Lobby system + matchmaking
- [RC] Dedicated server mode (headless)
- [RC] Asset store — community plugins and assets
- [RC] Pro tier launch ($19/mo)
- [RC] Enterprise tier for studios
- [RC] Console platform support investigation
- **Milestone**: Multiplayer games shipping, revenue from Pro tier

## Phase 5: Growth (Months 19-36)
- [RC] Console support (Switch, PlayStation, Xbox)
- [RC] VR/AR via OpenXR
- [RC] Procedural generation toolkit
- [RC] Dialogue system for narrative games
- [RC] Localization framework
- [RC] Replay system — deterministic recording
- [RC] Game jams + community events
- [RC] Studio partnerships
- **Milestone**: 1,000+ games shipped, sustainable revenue

## Investment
- **Target**: $5-10M over 36 months
- **Team**: Engine (Rust), Editor (Rust+egui), DevRel, Community
- **Revenue**: Core free, Pro $19/mo, Enterprise custom
- **Key Metric**: Games shipped on BlackRoad Engine

## Performance Targets
| Metric | Target | Current |
|--------|--------|---------|
| 2D sprites (60 FPS) | 500K | — |
| 3D entities (60 FPS) | 100K | — |
| Hot-reload time | <1 second | — |
| Binary size (minimal) | <15MB | — |
| Build time (incremental) | <5 seconds | — |
| WASM bundle size | <10MB | — |
