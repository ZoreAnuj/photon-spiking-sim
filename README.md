# Photon Spiking Sim

A silicon-photonic spiking neural network simulator exploring ultra-fast, energy-efficient neuromorphic computing. This project ports core photonic principles into a software simulation to model optical neural dynamics and training.

## Key Features
*   Simulates photonic spiking neurons and synaptic connections.
*   Leverages WebAssembly SIMD for accelerated numerical computation.
*   Implements real-time optical training algorithms (e.g., spike-timing-dependent plasticity).
*   Provides a browser-based visualizer for network activity.

## Tech Stack
*   C++ (Core simulation library)
*   WebAssembly (Emscripten) with SIMD
*   JavaScript/WebGL (Visualization frontend)

## Getting Started
```bash
git clone https://github.com/zoreanuj/photon-spiking-sim.git
cd photon-spiking-sim
make build-wasm
python3 -m http.server 8080 # Serve the `public/` directory
```