## ffmpeg video conversion for teaser

ffmpeg -i input.mp4 -vcodec h264 -crf 32  -vf "scale=-2:300,fps=30,crop=300:300" website_teaser.mp4
