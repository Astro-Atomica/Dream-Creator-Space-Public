# User guide

[Open Dream Creator Space](https://dreamcreatorspace.com/) · [Back to the repository](../README.md)

Dream Creator Space helps you plan a studio layout and inspect camera views before moving equipment. This guide describes the core workflow; controls may vary with the site's version and build.

## Start a layout

1. Set up the room dimensions in the **Room** panel. Add the openings and outlets relevant to your layout.
2. Choose equipment from the catalog and place it in the room. Generic furniture and gear can help you block out a layout before selecting exact products.
3. Select an item to edit its properties in the inspector. Use the viewport controls to position and rotate it.
4. Add a camera, choose its body and lens where supported, and aim it at your subject.
5. Adjust focal length, aperture, and focus distance, then inspect the camera's framing and focus preview.

Use `G` to select translation and `R` for rotation. Rotation normally snaps; hold **Shift** for free rotation. When a rotation ring is hovered, the scroll wheel steps that axis.

## Compare camera views

The **Views** panel lists cameras with previews. Open floating viewports to inspect multiple shots, drag their title bars to reposition them, and resize from the bottom-right corner. **Tile** arranges open views into a grid.

Each camera view supports these rendering modes:

| Mode | What it helps inspect |
| --- | --- |
| Realistic | The lit scene |
| True colour | Object colours without scene lighting |
| Focus | Distance in front of or behind the focus plane |
| Zebra | Highlighted brightness ranges |

## Organize equipment

Use groups to separate parts of a setup. The bill of materials summarizes quantities and wattage by group. Ownership information helps distinguish equipment you have from equipment you are considering.

Power planning connects gear through outlets, strips, splitters, and battery stations. Treat load and runtime estimates as planning aids; check equipment specifications and the actual electrical setup before use.

## Keep a backup

The app stores data in your browser. Clearing site data, switching browser profiles, or using another device can make those local saves unavailable.

Use **Export** to download a scene JSON file and **Import** to open a saved scene. A scene can depend on a room in your library; if an import says that room is missing, import or create the room first. Keep backups of the room/library data your scene needs as well as the scene itself.

Before attaching an export to a public issue, remove private layout details, inventory identifiers, and any personal data. A small fictional scene that reproduces the problem is preferable to your real studio.

## Understanding the preview

Camera previews are models of a setup, not measurements of a physical camera or lens. Depth of field and field of view depend on the modeled optics; lens-specific focus breathing is not modeled. Catalog entries can use approximate specifications, which are identified in the inspector.

Use the planner to compare layouts, then confirm framing, focus, lighting, and power with the actual equipment.

## Get help

For a problem, open **Settings → Report a bug**. That link fills in the version and build. Add reproduction steps, expected behavior, actual behavior, and your browser and operating system.

For an improvement, [open a feature request](https://github.com/Astro-Atomica/Dream-Creator-Space-Public/issues/new?template=feature_request.md) describing the problem you want to solve and how you would use the feature.
