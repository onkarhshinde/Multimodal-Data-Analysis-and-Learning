# Audio-Video Matching & Collision Detection

This project processes **audio and video files** to:
- Extract duration information.
- Detect **high-frequency peaks** in audio, which may indicate **collision events**.
- Use **Dynamic Time Warping (DTW)** and the **Hungarian Algorithm** for matching audio and video sequences.

---

##  Features

1. **Audio & Video Duration Analysis**
   - Extracts durations from `.wav` (audio) and `.mp4` (video) files.
   - Uses `librosa` for **audio processing** and `cv2` for **video processing**.
   - Counts occurrences of different durations.

2. **Collision Detection in Audio**
   - Computes **Short-Time Fourier Transform (STFT)**.
   - Normalizes energy levels and detects peaks using `find_peaks`.
   - Visualizes detected **collision peaks** in audio.

3. **Audio-Video Matching**
   - Uses **Dynamic Time Warping (DTW)** to find similarities between **audio** and **video** events.
   - Uses the **Hungarian Algorithm** to determine the optimal matching between detected peaks.

---

 
## Folder Structure
```
📂 dataset/
 ├── 📂 audio_only/       # Contains .wav files
 ├── 📂 video_only/       # Contains .mp4 files
📄 finalmatching_code_for_processing.ipynb  # Python script for processing      
📄 processing_dtw_matches.csv               # CSV - Stores mapping of audio to video with dtw loss
📄 processing_Hungarian_dtw_matches.csv     # CSV - Stores mapping of audio to video with dtw loss using Hugarian algorithm
📄 submit_solution_mapping.csv              # CSV - Stores matched peaks (Audio ↔ Video) {FINAL}
📄 collision_timestamps.txt                 # TXT - Stores video collsion timestamps
```
---

##  Sample Plots
Collision Peaks in Audio
![output](https://github.com/user-attachments/assets/03b1cd4b-8af3-4d0c-bcd9-fe22cd476ef6)

Collision Peaks in Video
![output](https://github.com/user-attachments/assets/80e156d6-82ba-4776-9ab3-c26abc028037)

---













