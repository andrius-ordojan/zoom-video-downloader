# zoom-video-downloader 

Download zoom videos from shared links. 
Has the ability to enter the passcode and submit the form. 

## Usage

Basic:

```
uv run main.py https://zoom.us/rec/share/your-link
```

Custom filename:

```
uv run main.py https://zoom.us/rec/share/your-link -o meeting.mp4
```

Enter password:

```
uv run main.py https://zoom.us/rec/share/your-link -p password
```
