# Spotify Genre Predictor: Metal vs. Classical

**Course:** Fundamentals of AI and ML - BYOP 

**Author:** Parth Shende (25BCE10024)

**College:** VIT Bhopal University

## 1. What's the problem and how did I solve it?
Sorting through thousands of songs to build perfect playlist takes forever. It's especially hard to quickly separate completely different vibes—like the heavy metal track versus acoustic classical piece.

Instead of sorting music by hand, I built a Machine Learning model to do it automatically. But instead of making the AI "listen" to heavy audio files (which takes tons of computer power), I used Spotify's official track data from kaggle. The model looks at the actual math behind the music—things like the tempo,the loudness, and how much electric guitar it has,to instantly predict if a song is Metal, Classical, or Indian music.

## 2. How to get this running on your computer
If you have never looked at this code before. Just follow these quick steps:

**What you need first:**
* Python installed on your computer, OR you can just use Google Colab (which is way easier).

**Step-by-step setup:**
1. Download or clone this project folder to your computer:
   `git clone https://github.com/parth1914/spotify-genre-classifier`
2. Open your terminal, go into the project folder, and install the required tools:
   `pip install -r requirements.txt`
3. Get the data, Download the Spotify Tracks Dataset from Kaggle:(https://www.kaggle.com/datasets/yashdev01/spotify-tracks-dataset/data).
4. Unzip that download and drop the `.csv` file right next to my code file.

## 3. How to actually use it
1. Open up the `spotify_classifier.ipynb` file (you can use Jupyter, VS Code, or upload it to Google Colab).
2. Look at the very first block of code. Change the `file_path` line so it points to wherever you saved the Kaggle `.csv` file.
3. Hit "Run All" in your code editor.
4. The code will automatically load the music data, draw a graph showing the visual difference between the genres, train the AI, and print out exactly how accurate the predictions are.
