# YouTube Audio Downloader

A simple desktop application built with Python and Tkinter to search for and download the audio track from YouTube videos as high-quality FLAC files.


### Preview

https://private-user-images.githubusercontent.com/76011651/474742629-8849e30f-e763-4a4f-a041-dcb1ee351012.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTQ0NzE4OTUsIm5iZiI6MTc1NDQ3MTU5NSwicGF0aCI6Ii83NjAxMTY1MS80NzQ3NDI2MjktODg0OWUzMGYtZTc2My00YTRmLWEwNDEtZGNiMWVlMzUxMDEyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODA2VDA5MTMxNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE4ZDViNjgzMzJkZTk4NjM4YjNlNmI0MzFhZWYyMDRiODIxNmM1ZmZkYThjYzU0NTJlN2YzNTUyNTE5NmMxZDMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.HUclh0PUX6yeIkUyY_UP6aL_ardhKS6IqZ0bj2VVFTo<img width="800" height="674" alt="image" src="https://github.com/user-attachments/assets/47512506-cf77-41ae-86ba-555aaeaa54b1" />




[![grafik](https://private-user-images.githubusercontent.com/76011651/474743625-325677d5-bd76-4da2-b65b-7ac40811f3eb.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTQ0MzM1NTgsIm5iZiI6MTc1NDQzMzI1OCwicGF0aCI6Ii83NjAxMTY1MS80NzQ3NDM2MjUtMzI1Njc3ZDUtYmQ3Ni00ZGEyLWI2NWItN2FjNDA4MTFmM2ViLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MDUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODA1VDIyMzQxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBlNTI1ZmVkN2EzMGUzYWJhOTgwMjk5MWM0YTlmYTFiM2Q4OTFhMzRkOGVkMWYwMjc5YWVkYTg0ZmY0MGU0ZmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.5jkJ08N1KSR8lJOvUuUk5zRhxURr87Gf5AJFiQHsHEI)](https://private-user-images.githubusercontent.com/76011651/474743625-325677d5-bd76-4da2-b65b-7ac40811f3eb.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTQ0MzM1NTgsIm5iZiI6MTc1NDQzMzI1OCwicGF0aCI6Ii83NjAxMTY1MS80NzQ3NDM2MjUtMzI1Njc3ZDUtYmQ3Ni00ZGEyLWI2NWItN2FjNDA4MTFmM2ViLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MDUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODA1VDIyMzQxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBlNTI1ZmVkN2EzMGUzYWJhOTgwMjk5MWM0YTlmYTFiM2Q4OTFhMzRkOGVkMWYwMjc5YWVkYTg0ZmY0MGU0ZmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.5jkJ08N1KSR8lJOvUuUk5zRhxURr87Gf5AJFiQHsHEI)


### Features

- Song Search: Search for songs or videos directly by name.

- Results List: Displays the top search results with titles and thumbnails.

- Easy Selection: Click on a search result to select it for download.

- High Quality: Downloads the best possible audio quality and converts it into a FLAC file.

- Intuitive Interface: A simple and easy-to-understand graphical user interface.


### Prerequisites

- Before you can run the script, you need to have a few things installed and set up:

- Python 3: You need an installed version of Python 3.

- FFmpeg: This program is required to convert the downloaded video files into FLACs.
         Download it from gyan.dev/ffmpeg/builds/.
    
- Extract it into a folder (e.g., C:\ffmpeg). Important: You must add the bin subfolder (e.g., C:\ffmpeg\bin) to your system's environment variables (Path).
    
Python Libraries: You will need the following Python packages: 
-  yt-dlp 
- Pillow 
- requests


## Disclaimer

This project is for educational purposes only. Downloading copyrighted material may violate YouTube's terms of service and the laws of your country. Please use this tool responsibly and respect copyright laws.
