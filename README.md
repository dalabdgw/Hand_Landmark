# Hand posture detection🤚🏻
This code helps you to get hand landmark especially when playing piano or violin.
## Code Requirements 💻
* Python
* OpenCV
* Mediapipe
* FFmpeg
## Description ✏️
```video_to_csv``` performs hand shape recognition using the MediaPipe Hands library. 
It recognizes hand shapes for a given set of images, extracts landmark locations for each hand, and stores them as data.
```audio``` extracts audio from a video file using FFmpeg. 
It extracts 1 second of audio from a given video file and saves the extracted audio as an MP3 file.
```MFCC``` saves the MFCC features extracted from the file, reads skeleton data from a CSV file, and extracts data for the desired columns from a specified range of frames.
## Output 🎻
<img src='./output_frame_8301.jpg'>
