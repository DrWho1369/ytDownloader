# YouTube Video Downloader

This simple Python program uses the `pytube` library to download YouTube videos. It's a command-line tool that takes a YouTube video URL as an argument and downloads the video in the highest resolution available.

## How to Use

1. Make sure you have Python installed on your system.
2. Install the required library by running:
   ```bash
   pip install pytube
   ```

3. Run the script with the YouTube video URL as an argument:
   ```bash
   python youtube_downloader.py <video_url>
   ```
   Replace `<video_url>` with the actual URL of the YouTube video you want to download.

4. The program will display information about the video, including title and views.

5. The highest resolution stream of the video will be downloaded to the specified directory (`C:/Users/Tom Baker/Downloads/YouTubeDownloads` in this case).

## Dependencies

- `pytube`: A lightweight, dependency-free Python library to download YouTube videos.

## Example

```bash
python youtube_downloader.py https://www.youtube.com/watch?v=your_video_id
```

## Note

Ensure you comply with YouTube's terms of service and copyright regulations while using this tool. Downloading videos without permission may violate YouTube's policies.

Feel free to explore, contribute, and enhance this YouTube Video Downloader. If you have any questions or suggestions, please open an issue.

---

**Disclaimer:** This tool is intended for personal use, and users are responsible for ensuring compliance with all relevant legal and ethical guidelines.
