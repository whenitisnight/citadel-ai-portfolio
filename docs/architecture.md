# Architecture

The HTML document owns the reading order and navigation. Scroll position is normalized across the chapters and mapped onto a Three.js camera path. Direct stage links move through that same route, update browser history and place keyboard focus on the destination heading. User scrolling can interrupt an animated transition.

The current scene uses authored procedural geometry, local Three.js modules, environmental lighting, floor reflections and restrained bloom. Structures alongside and above the route make camera travel perceptible. Fonts and runtime modules are served locally. The current entry does not need the older retail scene's Blender assets, although those editable assets remain preserved with that version.

Rendering pauses when the document is hidden or a dialog is open. Reduced motion disables ambient movement and continuous camera travel. The scene is separate from the semantic HTML controls, so a simulated WebGL initialization failure does not remove navigation, the sample result or the local contact-brief interaction.

The workflow's inputs, context and outputs are authored examples. The brief is local page memory and copying requires an explicit action. No business API or message-sending backend is connected to the demonstration.

The source repository keeps the major design revisions as named branches or tags. This independent public library contains selected explanations and evidence, with no private implementation history copied into it.
