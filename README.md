# defaultcf.github.io

## Make background image

```shell
convert -resize 1500x1000 a.jpg b.jpg
convert b.jpg -sampling-factor 4:2:0 -strip -quality 85 -interlace JPEG -colorspace sRGB c.jpg
```
