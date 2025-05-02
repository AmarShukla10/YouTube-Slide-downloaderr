## 🎞️ YouTube Slide Downloader

**YouTube Slide Downloader** is a desktop application that allows you to extract slide images from educational YouTube videos and save them as individual images or a single PDF document. Ideal for students, teachers, and learners who want to save study materials quickly and efficiently.


### ✨ Features

* 📥 Download and analyze YouTube videos
* 🧠 Automatically detect slide transitions using visual and text comparison
* 🖼️ Save slides as PNG images
* 📄 Export slides into a single PDF file
* 💻 User-friendly graphical interface (Tkinter)


### 🛠️ Requirements

* Python 3.7+
* [yt-dlp](https://github.com/yt-dlp/yt-dlp) (for video downloading)

Python packages are listed in `requirements.txt`. Install them using:

```bash
pip install -r requirements.txt
```

### 📂 Installation

1. Clone this repository:

```bash
git clone https://github.com/AmarShukla10/youtube-slide-downloader.git
cd youtube-slide-downloader
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. (Optional) Ensure `yt-dlp` is in your system path or install it via:

```bash
pip install yt-dlp
```


### 🚀 Usage

#### GUI Mode (Recommended)

Run the GUI:

```bash
python main.py
```

* Paste the YouTube video URL
* Set the frame interval (in seconds) and similarity threshold (0.0–1.0)
* Click **Extract Slides**
* Click **Generate PDF** to export the extracted slides

#### CLI Mode (Advanced)

```bash
python slide_extractor.py "https://www.youtube.com/watch?v=YOUR_VIDEO_ID" --interval 5 --threshold 0.9
```

Arguments:

* `url`: YouTube video URL
* `--interval`: Time (in seconds) between frames checked (default is 5)
* `--threshold`: Similarity threshold for slide changes (default is 0.9)


### 📁 Output

* All slide images are saved in the `slides/` folder.
* PDF file will be generated in the selected output location.


### 🔒 Disclaimer

This tool is intended for **educational and personal use only**. Please respect content creators’ copyrights and terms of service when using content.


### 👨‍💻 Author

Developed by Amar Shukla
