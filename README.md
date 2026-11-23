# Photo Memory Room

A single-page three.js recreation of a 1990s flash snapshot room, from the *Ten Minutes Until Closing* VR project (UW TECHIN 599).

- Open `index.html` through any static server (or GitHub Pages). The model and textures are embedded in the page; three.js and cannon-es load from jsDelivr.
- Drag the clear box, its lid or the clothes to pick them up and throw them. Pull the bedside drawer out by its knob. Push the rooster rocker (from the first-birthday photo) to set it rocking. Brush or tap the curtain to make it sway (it is hung, not grabbable).
- Buttons: Photo view, Film look, Flash, Reset objects.

Built procedurally in Blender (`tools/export_photo_room_web.py`) and packed by `tools/build_photo_room_web.py` in the main project. Lighting and film grade approximate the Unity scene `PhotoRoom_Lit.unity`.
