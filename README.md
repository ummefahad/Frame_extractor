# Frame_extractor

#**YouTube Video Frame Extractor**
Overview
This Python script allows you to extract frames from YouTube videos and save them as image files. It utilizes the pytube library to download the video and OpenCV (cv2) to extract frames.

***Features**
Extract frames from YouTube videos.
Save extracted frames as image files.
Display the video while extracting frames (optional, for local environments).
**Requirements**
Python 3
pytube library
opencv-python library
**Usage**
Install the required libraries:
Copy code
pip install pytube opencv-python
Run the script with the YouTube video URL as an argument:
arduino
Copy code
python frame_extractor.py https://www.youtube.com/watch?v=YOUR_VIDEO_ID
Replace YOUR_VIDEO_ID with the actual video ID from YouTube.
The frames will be saved in the current directory as image files.
Example
To extract frames from a YouTube video with the URL https://www.youtube.com/watch?v=xZxh4NF-xy4, you would run:

python frame_extractor.py https://www.youtube.com/watch?v=xZxh4NF-xy4
Note
This script may not work in certain environments where access to YouTube is restricted.
Use responsibly and respect copyright laws when downloading and using video content

O/p
![image](https://github.com/ummefahad/Frame_extractor/assets/110823502/57c9ada6-f9ee-4fbf-8e73-325731f60874)
![image](https://github.com/ummefahad/Frame_extractor/assets/110823502/964ffc40-e38f-4c6d-9a76-c8a71699b814)

