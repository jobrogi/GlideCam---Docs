# GlideCam – Lite RTS Camera System

**Version:** 1.0.0  
**Supported UE Versions:** 5.3, 5.4, 5.5, 5.6  
**Author:** Ghillie Studios  
**Support:** [Discord](https://discord.gg/6xmYHNKk)  
**Showcase Video:** [Watch on YouTube](https://youtu.be/Fhj3NfSXJv4)

---

## Overview

GlideCam is a modular RTS-style camera system designed for strategy, simulation, and top-down games. Built entirely with Blueprints and Enhanced Input, it offers smooth glide movement, zooming, snapping, and full runtime control with zero C++ setup.

---

## Installation

1. Copy the `GlideCam` plugin folder to your project's `Plugins` directory:

2. Open your project and enable the **Enhanced Input** plugin (Edit → Plugins → Search "Enhanced Input").

3. Add the `BP_GlideCamPawn` Blueprint to your level and set it as the default Pawn or possess it at runtime.

---

## Default Controls

| Action              | Input                 |
|---------------------|------------------------|
| Move Camera         | W / A / S / D          |
| Rotate Camera       | Q (left), E (right)    |
| Snap Rotation       | Z (left), C (right)    |
| Reset Orientation   | R                      |
| Zoom                | Mouse Scroll Wheel     |
| Drag Pan (RTS-style)| Right Mouse Drag       |

All input actions can be customized through the `IMC_GlideCamControls` mapping context.

---

## Key Features

- ✅ Smooth glide-based camera movement
- ✅ Zooming and rotation with inertia
- ✅ Snapping to 90° angles
- ✅ RTS-style mouse drag panning
- ✅ Blueprint-only system — no C++ required
- ✅ Fully modular and easy to integrate
- ✅ Enhanced Input support out-of-the-box

---

## Components

- `BP_GlideCamPawn`: Main camera controller Blueprint.
- `IMC_GlideCamControls`: Input Mapping Context.
- `IA_*`: Input Actions for movement, rotation, etc.

---

## Notes

- ⚠️ **Requires Enhanced Input plugin** — this must be enabled in your project.
- You can expose camera speed, damping, and other settings via Blueprint variables.
- Snapping angle and zoom limits can be customized in the editor.

---

## Troubleshooting

**Camera not responding to input?**  
→ Make sure `BP_GlideCamPawn` is possessed and `IMC_GlideCamControls` is applied at runtime.

**Input Actions show as missing?**  
→ Reimport the plugin properly. Ensure Enhanced Input is enabled before loading the project.

---

## License

You are free to use GlideCam in personal and commercial Unreal Engine projects. Do not resell or redistribute the plugin source.

---

For support and updates, join the community: [https://discord.gg/6xmYHNKk](https://discord.gg/6xmYHNKk)
