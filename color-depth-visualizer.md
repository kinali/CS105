---
layout: default
title: Color Depth Visualizer
parent: Information Layer
grand_parent: Layers
has_children: true
nav_order: 1
---

# Color Depth Visualizer

Use the controls in the embedded app to compare:

- High Color (16-bit RGB565)
- True Color (24-bit RGB888)
- Deep Color (10-bit RGB101010)

[Open full app in new tab]({{ '/color-depth-viz/index.html' | relative_url }}){: target="_blank" }

<div style="position:relative; width:100%; height:80vh; min-height:700px;">
  <iframe
    src="{{ '/color-depth-viz/index.html' | relative_url }}"
    style="position:absolute; inset:0; width:100%; height:100%; border:1px solid #ccc; border-radius:8px;"
    loading="lazy">
  </iframe>
</div>
