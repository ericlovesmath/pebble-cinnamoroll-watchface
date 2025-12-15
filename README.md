# Cinnamoroll Pebble Watchface

Watchface for the Pebble Time watch. Supports Basalt, Emery, and Chalk.

![Demo](./screenshots/demo.png)
![Basalt](./screenshots/basalt.png)
![Emery](./screenshots/emery.png)
![Chalk](./screenshots/chalk.png)

Font: [MochiBop](https://www.1001fonts.com/mochibop-font.html)

```bash
# Images generated primarily for Pebble Time, modify for different watch faces
magick cinnamoroll.png -colors 64 -depth 8 -define "png:color-type=6" -sample 144x168 roll~color.png
magick cinnamoroll.png -colors 64 -depth 8 -define "png:color-type=6" -sample 144x168 -colorspace Gray -gamma 0.8 roll~bw.png
```
