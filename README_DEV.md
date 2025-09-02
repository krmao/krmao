## video compress

```sh
ffmpeg -i ai-preview.mp4 -c:v libx264 -crf 29.4 -c:a aac -b:a 96k -fs 10M ai-preview-10mb.mp4

ffmpeg -i ai-display.mov -vf "scale=trunc(iw/2)*2:trunc(ih/2)*2" -c:v libx264 -crf 22 -c:a aac -b:a 128k ai-display-10mb.mp4
```
