# 🎬 Mood Movie Recommender

Capture a photo of yourself right from your webcam, and this tool reads your facial expression in that exact moment to tell you what genre fits your mood — then recommends real movies to match it.

No forms, no ratings to fill in — just look at the camera, press a key, and get a personalized movie suggestion based on how you're feeling right now.

## ✨ Features

- Captures a live photo directly from your webcam
- Detects your dominant facial emotion at that moment: happy, sad, angry, surprised, fearful, disgusted, or neutral
- Automatically maps your emotion to a fitting movie genre
- Recommends real movies from a curated list matching that genre
- Simple one-key interaction — no complicated menus or setup during use

## 📦 Requirements

- Python 3.9 or newer
- A working webcam
- Internet connection on first run only (to download the emotion detection model automatically)

## 📥 Clone the Repository

```bash
git clone https://github.com/kamandNajari/Mood_Movie_Recommender.git
cd Mood_Movie_Recommender
```

## 🚀 Installation

Install all required libraries with a single command:

```bash
pip install -r requirements.txt
```

This installs:
- **opencv-python** — for accessing the webcam and displaying images
- **deepface** — for facial emotion recognition

## 📓 Running the Notebook

Make sure Jupyter is installed:

```bash
pip install jupyter
```

Then launch it:

```bash
jupyter notebook
```

Open `mood_movie_recommender.ipynb` from the Jupyter interface and run the cell (Shift + Enter).

## ▶️ How to Use

1. Run the notebook cell — your webcam will open in a new window
2. Get your natural expression ready in front of the camera
3. Press **SPACE** to capture the photo and analyze it
4. Press **q** at any time if you want to quit without capturing
5. The tool then prints:
   - Your detected emotion
   - A suggested movie genre based on that emotion
   - Three recommended movies to watch right now

## 🛠️ Tech Stack

- [DeepFace](https://github.com/serengil/deepface) — facial emotion recognition model
- [OpenCV](https://opencv.org/) — webcam capture and image display

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

Thank you for checking out this project! ✨
