### Leo — LM Studios

I build real-time graphics and music tools, mostly on macOS and Linux.

**Current**

- **MetalStage** — native Swift + Metal live-visuals engine for macOS: 116-shader catalog, MIDI / audio / Ableton Link modulation, layers, meshes, gaussian splats, modular node graph, Performance Mode with a second-screen output. The Mac sibling of VulkanStage.
- **VulkanStage** — from-scratch real-time visuals engine in Rust on raw Vulkan (`ash`): GLSL shader catalog, arrangement timeline, OSC / MIDI / audio modulation, water, splats, meshes.
- **Reef** — GPU-accelerated terminal in Rust / gpui for macOS and Linux, built for working with AI coding agents: tiling WM mode, tab groups, built-in browser, sessions that survive quitting, MCP bridge for Claude Code.
- **[ilanaSynth](https://github.com/Le0-SD/ilanaSynth)** — Mac port and improvements of a physical-hybrid JUCE synthesizer (strings, bows, hammers, wavetable, FM, granular; VST3 / CLAP / AU).
- **Elektron Digitakt II tooling** — firmware research, custom patches and an MCP server that plays the box from a terminal ([digikit](https://github.com/Le0-SD/digikit) fork).

**Earlier**

- **ShaderMIDI** — Metal shader instrument for MIDI-controlled live visuals with Ableton Link sync; grew into MetalStage.
- **PixelPipe / Lucid / OrganiVision** — macOS screen perception, memory and control exposed through MCP servers.

**Stack:** Swift, Metal, Rust, Vulkan, C++ (JUCE), Python, TypeScript.

I like tools that stay close to the OS and to the hardware, and make the computer easier to steer.
