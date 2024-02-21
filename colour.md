# Colour

The bangle.js 2 is 3-bit, meaning that there are only 8 colours. However, using dithering, we're able to display more colours. Dithering is hard on the small, 176x176 display, and can reduce bad results if not done properly. 

| Binary | Hex Code | Color Name |
|--------|----------|------------|
| 000    | `#000000` | $${\color{#000000} \text{Black}}$$   |
| 001    | `#FF0000` | $${\color{#FF0000} \text{Red}}$$        |
| 010    | `#00FF00` | $${\color{#00FF00} \text{Green}}$$    |
| 011    | `#0000FF` | $${\color{#0000FF} \text{Blue}}$$      |
| 100    | `#FFFF00` | $${\color{#FFFF00} \text{Yellow}}$$  |
| 101    | `#00FFFF` | $${\color{#00FFFF} \text{Cyan}}$$      |
| 110    | `#FF00FF` | $${\color{#FF00FF} \text{Magenta}}$$|
| 111    | `#FFFFFF` | $${\color{#FFFFFF} \text{White}}$$    |
