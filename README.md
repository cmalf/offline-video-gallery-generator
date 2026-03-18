# Offline Video Gallery Generator

A simple PHP script that scans a local folder of videos and generates a standalone HTML video gallery.

## Features

- Scan a local directory for video files
- Filter by selected video extension
- Generate a standalone HTML gallery page
- Built-in main video player
- Search videos by title
- Previous / next navigation buttons
- Play / pause, fullscreen, and mute controls
- Dark / light theme toggle
- Keyboard shortcuts for playback and volume control
- Works well for offline local collections

## Supported Video Extensions

- MP4
- AVI
- MKV
- MOV
- WMV
- FLV
- 3GP
- WEBM
- MPEG
- VOB
- DAT
- TS

## Requirements

- PHP 7.4 or newer
- A local folder containing video files

## Usage

1. Place the script in any directory.

2. Run it with PHP:
   ```bash
   php ovgg.php
   ```

3. Select the video extension format.

4. Enter the directory path containing your videos.

5. Enter the title for the generated HTML page.

6. Enter the output file name.

7. Open the generated `.html` file in your browser.

Notes

   -  This project is designed for local or offline use.

   -  Video paths are based on your selected folder.

   -  Make sure the generated HTML file stays in the correct location relative to your videos.

## License

Released under the MIT License. You are free to use, modify, and distribute this project. See the [LICENSE](LICENSE) file for more information.
