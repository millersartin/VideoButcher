# Video Butcher

Video Clipper is a Python script that allows you to automatically segment videos into smaller clips of a specified duration. You can source videos directly from YouTube or use local files from your hard drive.

## Features

- **YouTube Video Download**: Easily download videos from YouTube by providing the video URL.
- **Video Segmentation**: Automatically segment videos into smaller clips of a specified duration.
- **Local and YouTube Video Support**: Source videos from YouTube or use local files from your hard drive.

## Usage

1. **Download or Identify Video**: Start by either downloading a video from YouTube using its URL or identifying a video file on your hard drive that you'd like to segment.
   
2. **Specify Clip Duration**: Determine the duration of each clip segment. For instance, specifying a 3-minute duration will segment a 9-minute video into three 3-minute clips.

3. **Run the Script**: Execute the script with the necessary parameters to initiate the video segmentation process.

```python
# Example usage
python video_clipper.py --source "path/to/local/video or YouTube URL" --clip-duration 3
```
## Installation

Ensure you have Python 3.x installed on your system. You can download it from the [Python official website](https://www.python.org/).

1. **Clone the Repository**
   
   Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your_username/your_project_name.git

2. **Install Dependencies**

   ```bash
   pip install yt-dlp
   pip install python-ffmpeg
   ```
