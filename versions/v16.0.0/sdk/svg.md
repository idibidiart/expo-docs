---
title: Svg
---

### `Svg`

A set of drawing primitives such as `Circle`, `Rect`, `Path`, `ClipPath`, and `Polygon`. It supports most SVG elements and properties. The implementation is provided by [react-native-svg 4.1.3](https://github.com/magicismight/react-native-svg/tree/c9a64c44fcf48b57b2401925950befa3727deb24), and documentation is provided [in that repository](https://github.com/magicismight/react-native-svg/tree/c9a64c44fcf48b57b2401925950befa3727deb24).

Usage:
```
  `import { Svg } from 'expo';`

  <Svg height={100} width={100}>
    <Svg.Circle
      cx={50}
      cy={50}
      r={45}
      strokeWidth={2.5}
      stroke="#e74c3c"
      fill="#f1c40f"
    />
    <Svg.Rect
      x={15}
      y={15}
      width={70}
      height={70}
      strokeWidth={2}
      stroke="#9b59b6"
      fill="#3498db"
    />
  </Svg>
```


