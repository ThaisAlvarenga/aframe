---
title: <a-gltf-model>
type: primitives
layout: docs
parent_section: primitives
source_code: src/extras/primitives/primitives/a-gltf-model.js
---

The glTF model primitive displays a 3D glTF model created from a 3D
modeling program or downloaded from the web. Overall, glTF models are more reliable format to work with in the web.

## Example

```html
<a-scene>
  <a-assets>
    <a-asset-item id="tree" src="tree.gltf"></a-asset-item>
  </a-assets>

  <!-- Using the asset management system. -->
  <a-gltf-model src="#tree"></a-gltf-model>

  <!-- Defining the URL inline. Not recommended but more comfortable for web developers. -->
  <a-gltf-model src="tree.gltf"></a-gltf-model>
</a-scene>
```


## Attribute

For a more comprehensive desription of what gltf models are and how they work on A-frame, check the attribute documentation. 

[gltf]: ../components/gltf-model.md

| Attribute | Component Mapping      | Default Value |
|-----------|------------------------|---------------|
| src       | [gltf-model][gltf].src | null          |

To change your OBJ model to gltf, you can try using [the > converter](https://cesiumjs.org/convertmodel.html) or try out the [OBJ > converter](https://github.com/AnalyticalGraphicsInc/OBJ2GLTF).