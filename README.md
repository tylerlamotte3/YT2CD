# YT2CD

YT2CD is a script I made for Arch Linux that simplifies the process of downloading audio from YouTube, converting the audio into the propper format and including metadata, and burning to CDs. I hated typing song names into k3b manually.

If you just want to download a youtube playlist with metadata you can download cddownload.sh and cancel the script when it asks for your cd drive location.

## Prerequisites

- yt-dlp(https://github.com/yt-dlp/yt-dlp)
- ffprobe (part of ffmpeg, https://www.ffmpeg.org/)
- cdrdao (https://github.com/cdrdao/cdrdao)

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/ghxst8/YT2CD.git
cd YT2CD
```

or just download the files from the code section.

## Usage

1. Run the script:

   ```bash
   chmod +x cddownload.sh
   chmod +x generatecue.sh
   ./cddownload.sh
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- yt-dlp(https://github.com/yt-dlp/yt-dlp)
- ffprobe (part of ffmpeg, https://www.ffmpeg.org/)
- cdrdao (https://github.com/cdrdao/cdrdao)

## Support

If you encounter issues or have questions, please open an issue on the [GitHub repository](https://github.com/ghxst8/YT2CD/issues).
