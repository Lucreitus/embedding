# Roadmap

## Embeddings

- Force-directed layout, including gravitational attraction, repulsion, springs, viscosity; possible starting points include
- Embedding "chaining" via events
- Aggregate embedding: display summary functions of data points that update as DPs are added/removed, possibly with filters, possibly grouped or binned

## Effects 

- Rigid-body interactions and gravity
- "Wind" and perturbation
- Directional lighting and shadows
- Moving lighting

## Interactivity

- Default navigation: teleportation
- Haptic feedback on supported browsers/controllers
- Spatialized sound effects on events
- Selection model and operations

## Data Sources

- SQL query loading into Dataset

## Integrations

- [AltspaceSDK](https://developer.altvr.com/)
- [A-Frame](https://aframe.io/docs/0.4.0/guides/using-with-threejs.html)

## Builds / Packaging

- Automated testing and CI
- Build status, code coverage, etc. reported in README widgets
- Clean up dependencies to use node_modules where possible (rather than script tags)
