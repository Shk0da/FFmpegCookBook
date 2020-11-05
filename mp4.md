
## Compress mp4 

ffmpeg -i input.mp4 -vcodec h264 -acodec mp2 output.mp4

ffmpeg -i input.mp4 -vcodec libx265 -crf 28 output.mp4
