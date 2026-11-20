# Architecture

The browser renders a real mesh scene with Three.js. Authored camera destinations and bounded route sampling move between the street, shop and counter; navigation can settle immediately when motion is disabled. Rendering is requested as the camera or demonstration changes.

The asset pipeline uses Blender-authored geometry and CC0 detail assets, Cycles illumination baked into denoised atlases, and Draco-compressed mesh delivery. Runtime loaders, fonts and decoder assets are served locally. The counter tablet and translucent stock card update their textures from the browser's demonstration state.

The workflow separates inquiry, stock inspection, draft reply and confirmation. Sample stock changes only on the confirmation step, and reset restores the fixture. These stages demonstrate an interaction pattern; they are not model inference or a real business transaction.

The private repository preserves both the deployed runtime and editable authoring assets, with older website directions retained as named Git checkpoints. The public library is independently authored documentation, not a copy of that source history.
