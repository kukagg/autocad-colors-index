## AutoCAD Colors Index

Simple map by ACI, HEX and RGB.

**Usage**

```js
const colorsMapper = require('autocad-colors-index')

const aci = colorsMapper.getByACI(255)
const hex = colorsMapper.getByHEX('#ffffff')

console.log(aci.hex === hex.hex) // true
console.log(aci.rgb) // has rgb too
```
