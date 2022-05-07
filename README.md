# ffmpeg-frontend-twitter-upload

rename of `fixedImageVideoConvert`
output video file for Twitter / YouTube with ffmpeg. ( depend on ffmpeg )

## Correctly working checked ffmpeg version with:
* ffmpeg version >= 4.3.1

## Limitations

* Twitter only accepts the video shorter than 1:30.

## Syntax

```bash
./vidconv.sh OUTPUT_FILE_PATH INPUT_PICT_PATH INPUT_MP3_PATH
```

* OUTPUT_FILE_PATH
  * .mp4 filename. does not overwrite.
* INPUT_PICT_PATH
  * .jpg, .png, .webp, and so on
* INPUT_MP3_PATH
  * .mp3, .aac, .ogg, and so on

## If you use MacOS

* This command notifies you ending process by voice.
