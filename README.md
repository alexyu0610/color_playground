# Color Playground

| Library / Framework   | Tasks |
| --------------------- | -------------------- |
| `chroma.js`           | takes care of hex-to-rgb conversion, bit manipulation involved for tweaking color brightness, saturation etc.        |

## Subtle features
1. Clicking on the hex code copies the color code to clipboard.
1. Sliders for adjusting hue, brightness and saturation update dynamically with the corresponding background color when new color is generated.
1. Every save writes directly to the library object which is then pushed to `localstorage` to keep the palette collections intact after a page refresh.

