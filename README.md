# Cards and Stories

Use ImageMagick to resize and convert images to the WebP format in bulk.

```bash
magick mogrify -resize 1200x -quality 80 -format webp *.jpg
```

Group photos in the same group with the lightbox effect.

```
![](mcmurdo-front.webp){fig-alt="front" style="background: white; padding: 10px; box-shadow: 0 12px 28px rgba(0,0,0,.55); border-radius: 2px;" group="mcmurdo"}

![](mcmurdo-back-address-crop.webp){fig-alt="back" style="background: white; padding: 10px; box-shadow: 0 12px 28px rgba(0,0,0,.55); border-radius: 2px;" group="mcmurdo"}
```