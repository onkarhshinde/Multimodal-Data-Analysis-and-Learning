# Multimodal Analysis of National Anthems, Flags, and Text Translations

This repository contains a multimodal dataset and analysis for exploring relationships between national flags, anthem lyrics, and anthem music compositions and also explores national anthems through three analytical perspectives: **visual analysis** of flags, **textual analysis** of anthem lyrics, and **audio analysis** of anthem music.

##  Repository Structure

```
📦 Multimodal-National-Anthems
│-- 📂 Results/                                      # Folder containing analysis outputs
│-- 📜 Audio Analysis.ipynb                          # Jupyter Notebook for audio analysis
│-- 📜 Dataset creation and Visual Analysis.ipynb    # dataset creation and Flags analysis
│-- 📜 Textual Analysis.ipynb                        # Jupyter Notebook for text analysis
│-- 📂 Dataset/
│   │-- 📂 Flags/                 # Contains flag images in PNG format
│   │-- 📂 Audio/                 # National anthem audio files (MP3)
│   │-- 📂 English_Translation/   # Anthem lyrics in English (TXT)
```

##  Dataset Overview

This dataset comprises three modalities:

1. **Flags**: Visual representations of country flags, extracted from various sources.
2. **Text Translations**: English lyrics of national anthems, pre-processed for textual analysis.
3. **Audio Files**: National anthems in MP3 format for acoustic analysis.

##  Analysis Breakdown

###  Visual Analysis (Flags)
- Extracted dominant colors and patterns from national flags.
- Identified common design elements like **stars, stripes, and symbols**.
- Compared flag similarities across different countries.

###  Textual Analysis (Lyrics)
- Processed text data by removing stop-words and analyzing word frequencies.
- Performed **sentiment analysis** to explore emotional tones in anthem lyrics.
- Investigated recurring themes such as **freedom, unity, history, and struggle**.

###  Audio Analysis (Anthem Music)
- Used `librosa` to extract key musical features.
- Separated **harmonic** and **percussive** components for better analysis.
- Analyzed **tempo, pitch variations, and rhythmic structures** to understand musical diversity.

### 🔗 Multimodal Correlation
- Investigated relationships between anthem sentiment, flag color themes, and music characteristics.

