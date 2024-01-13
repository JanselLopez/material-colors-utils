# material-colors-utils
Material color palettes. Random colors and palettes. Random colors and palettes by name or any string.

## Install

```npm
npm i material-colors-utils
```

## Colors

[🎨 Material Design Colors, Color Palette | Material UI](https://materialui.co/colors/)

## Usage
### Get random color
```js
import { getRandomColor } from "random-color-by-name";
//Param: Color variant
getRandomColor(300)//Ex: #64B5F6
//Default is 500
getRandomColor()//Ex: #2196F3
```

### Get random palette
```js
import { getRandomColor } from "random-color-by-name";
//Param: Color variant
getRandomColor(300)//Ex: #64B5F6
//Default is 500
getRandomColor()//Ex: #2196F3
```

```js
import { getRandomPalette } from "random-color-by-name";
console.log({palette:getRandomPalette()})
//{
//    palette:{
//      50: "#E3F2FD",
//      100: "#BBDEFB",
//      200: "#90CAF9",
//      300: "#64B5F6",
//      400: "#42A5F5",
//      500: "#2196F3",
//      600: "#1E88E5",
//      700: "#1976D2",
//      800: "#1565C0",
//      900: "#0D47A1",
//      A100: "#82B1FF",
//      A200: "#448AFF",
//      A400: "#2979FF",
//      A700: "#2962FF"
//    }
//}
```

### Get random palette by string
```js
import { getRandomPaletteByString } from "random-color-by-name";
console.log({palette:getRandomPaletteByString("janselALB")});
//{
//    palette:{
//      50: "#E3F2FD",
//      100: "#BBDEFB",
//      200: "#90CAF9",
//      300: "#64B5F6",
//      400: "#42A5F5",
//      500: "#2196F3",
//      600: "#1E88E5",
//      700: "#1976D2",
//      800: "#1565C0",
//      900: "#0D47A1",
//      A100: "#82B1FF",
//      A200: "#448AFF",
//      A400: "#2979FF",
//      A700: "#2962FF"
//    }
//}
```
### Get random color by string
```js
import { getRandomColorByString } from "random-color-by-name";
//Param: Color variant
getRandomColorByString("janselALB",300)//Ex: #64B5F6
//Default is 500
getRandomColorByString("janselALB")//Ex: #2196F3
```

### Get palette
```js
import { blue } from "random-color-by-name";
console.log({blue})
//{
//    blue:{
//      50: "#E3F2FD",
//      100: "#BBDEFB",
//      200: "#90CAF9",
//      300: "#64B5F6",
//      400: "#42A5F5",
//      500: "#2196F3",
//      600: "#1E88E5",
//      700: "#1976D2",
//      800: "#1565C0",
//      900: "#0D47A1",
//      A100: "#82B1FF",
//      A200: "#448AFF",
//      A400: "#2979FF",
//      A700: "#2962FF"
//    }
//}
```
### Get color
#### Example
```js
import { blue } from "random-color-by-name";
console.log(blue[500])//#2196F3
```
### Palettes
-  red
-  pink
-  purple
-  deepPurple
-  indigo
-  blue
-  lightBlue
-  cyan
-  teal
-  green
-  lightGreen
-  lime
-  yellow
-  amber
-  orange
-  deepOrange
-  brown
-  grey
-  blueGrey

### Variants
- 50
- 100
- 200
- 300
- 400
- 500
- 600
- 700
- 800
- 900
- A100 *(undefined in brown, grey and and blueGrey)*
- A200 *(undefined in brown, grey and and blueGrey)*
- A400 *(undefined in brown, grey and and blueGrey)*
- A700 *(undefined in brown, grey and and blueGrey)*
