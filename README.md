# Songs repository
This is a repository for free and openly licensed songs in ultrastar format for usage in sing-along karaoke games.

## Legal note
Do not add any song data to this repository unless you are the sole creator or you have written permission by the licensor / copyright holder to do so. Do not add any songs to this repository without also providing legally valid and correct licensing details. As contributor to this repository, it is your own responsibility to comply with any legal requirements in your country and to comply with any GitHub rules & terms.
If there is any content in this repository without legal permission, please send an email to copyright@usdx.eu and also create a new issue in the [issue tracker](https://github.com/UltraStar-Deluxe/songs/issues).

## Repository structure
| Where | What |
|---|---|
| / | Main repo folder. Try to not add any new files here, but instead place them in a fitting subfolder. |
| /Demo Samples/ | Song packs for demonstration- or development-purposes |
| /Public Domain/ | Song packs that are completely licensed under [Public Domain](https://creativecommons.org/share-your-work/public-domain/) or compatible licenses |
| /Creative Commons/ | Song packs licensed under a variation of [Creative Commons](https://creativecommons.org/) or compatible. |

## Song package structure
Each song in this repository has to follow this structure:
- one song per folder
- `Artist - Songtitle` as folder name
- `song.txt` as name for non-duet ultrastar song files
- `duet.txt` as name for duet ultrastar song files
- `instrumental.txt` as name for ultrastar song files with instrumental / no-voices audio file
- `audio.mp3` or `audio.ogg` as file name for the main audio file
- `instrumental.mp3` or `instrumental.ogg` as file name for the main audio file
- `video.mp4` or `video.webm` as file name for a small background video file
- `cover.png` or `cover.jpg` as file name for cover files. 1:1 image ratio
- `background.png` or `background.jpg` as name for the background image. prefer 16:9 image ratio
- `license.txt` in every song folder is required, even if all the media data and lyrics are licensed as public domain.

## Media formats
For video files, use h264 encoding and mp4 packaging. Keep the file size small. Remove any audio stream from the video file. Provide a link to a third party video hosting platform or video sharing service in the `song.txt` file as `#VIDEOSOURCE` tag instead of adding any big video files to this repository here, if necessary for good quality.
For audio files, target 192Kb/s CBR MP3 or 192Kb/s OGG Vorbis. All audio files should be stereo only.
Cover image files should be small, but not smaller than 400x400px in height and width.
Background images should target 1920x1080px size.
