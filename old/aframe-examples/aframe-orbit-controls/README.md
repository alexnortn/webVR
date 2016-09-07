## aframe-orbit-controls-component

An Orbit Controls component for [A-Frame](https://aframe.io) VR.

### Properties

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Usage

#### Browser Installation

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/latest/aframe.min.js"></script>
  <script src="https://raw.githubusercontent.com/subsumo/aframe-orbit-controls/master/dist/aframe-orbit-controls-component.min.js"></script>
</head>

<body>
    <a-scene>
      <a-camera target="#target" distance="1" orbit-controls look-controls-enabled=false wasd-controls-enabled=true position="0 0 0" ></a-camera>
      <a-sphere id="target" position="0 0 1" radius="0.1" color="#EF2D5E"></a-sphere>
      <a-sky src="https://upload.wikimedia.org/wikipedia/commons/8/83/Equirectangular_projection_SW.jpg"></a-sky>
    </a-scene>
</body>
```

#### NPM Installation

Install via NPM:

```bash
npm install aframe-orbit-controls-component
```

Then register and use.

```js
require('aframe');
require('aframe-orbit-controls-component');
```
