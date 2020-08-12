# WMV -> MP4 (HTML)
ffmpeg -i input.wmv -profile:v main -crf 20 -preset slow output.mp4
