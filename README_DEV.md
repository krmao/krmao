## video compress

```sh
ffmpeg -i ai-preview.mp4 -c:v libx264 -crf 29.4 -c:a aac -b:a 96k -fs 10M ai-preview-10mb.mp4
```
