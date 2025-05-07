# TribalMech_TextureFX

**Category:** Digital  
**Type:** TextureFX Shader for vvvv gamma (SDSL)  
**Author:** [Your Name or GitHub Handle]  
**License:** [Insert License, e.g. MIT]

---

## Overview

`TribalMech_TextureFX` is a shader written in **SDSL** for **vvvv gamma**. It generates glitchy, symmetrical patterns reminiscent of circuit diagrams and tribal-mechanical structures.  
The visual output is based on deterministic bitwise and arithmetic logic, allowing high customizability and unique generative compositions.

Perfect for:

- Procedural textures
- Live visuals
- Glitch and generative art
- Audio-reactive or feedback-based compositions

---

## Visual Style

- Symmetric circuit/glitch patterns  
- Boolean logic and mathematical structures  
- Clean yet complex visuals  
- Morphable between two distinct patterns

---

## Parameters

| Name        | Type           | Description |
|-------------|----------------|-------------|
| `Scale`     | `Float`        | Scales the coordinate space. Higher = more pattern detail. *(Default: `800`)* |
| `Modulus`   | `Float`        | Modulus used in the visibility logic. *(Default: `9970`)* |
| `Threshold` | `Float`        | Threshold for activating a pixel. *(Default: `1000`)* |
| `Complexity`| `Float`        | Increases pattern complexity. *(Default: `1.0`)* |
| `LogicDepth`| `Float`        | Adds logical depth (variation) to the formula. *(Default: `1.0`)* |
| `SeedA`     | `Float`        | Seed value for first pattern state. *(Default: `0.0`)* |
| `SeedB`     | `Float`        | Seed value for second pattern state. *(Default: `1.0`)* |
| `Morph`     | `Float (0–1)`  | Interpolates between SeedA and SeedB. *(Default: `0.0`)* |
| `SymmetryX` | `Float (bool)` | Enables horizontal symmetry. *(Default: `1.0`)* |
| `Time`      | `Float`        | Time factor for pattern evolution. *(Default: `0.0`)* |
| `Invert`    | `Float (bool)` | Inverts pixel logic. *(Default: `0.0`)* |
| `ColorOn`   | `Color` (RGBA) | Color of active pixels. *(Default: white)* |
| `ColorOff`  | `Color` (RGBA) | Color of inactive pixels. *(Default: black)* |




