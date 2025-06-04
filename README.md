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

## Installation (FAB Marketplace)

1. **Purchase and add the plugin** via the [Fab Marketplace](https://www.fab.com/portal/listings/e2c9ffb0-84cc-49fa-8ab4-3b98a4187ae3/edit).

2. **Inside the Epic Games Launcher**, go to the **Library** tab → locate `GlideCam` → click **Add to Project**.

![image](https://github.com/user-attachments/assets/362ad79b-a859-4099-8f73-b4273c0984b1)


3. In your Unreal Engine project, go to `Edit → Plugins`, search for **GlideCam**, and ensure the plugin is **enabled**.

![image](https://github.com/user-attachments/assets/f1827add-2b48-4f6b-9206-4eb7fd0ddf0b)

4. **Restart the engine** when prompted.

5. After restarting, the plugin content will appear under:  

![image](https://github.com/user-attachments/assets/2b2b9046-5298-4ef9-ad9b-e8bfd74d5068)

---

## Default Controls

| Action              | Input                 |
|---------------------|------------------------|
| Move Camera         | W / A / S / D          |
| Rotate Camera       | Q (left), E (right)    |
| Reset Orientation   | R                      |
| Zoom                | Mouse Scroll Wheel     |
| Drag Pan (RTS-style)| Right Mouse Drag       |

All input actions can be customized through the `IMC_GlideCamControls` mapping context.

---

## Key Features

- ✅ Smooth glide-based camera movement
- ✅ Zooming and rotation with inertia
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
