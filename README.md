# Music Playlist Embeddings (Colab-Only ML Project)

This project builds **song embeddings from playlists** using a Word2Vec-style approach.  
Playlists are treated as “sentences” and songs as “words”, allowing the model to learn musical similarity from co-occurrence patterns.

The entire project is designed to be developed **using Google Colab only**, while maintaining **professional ML and Git best practices**.

---

## 🎯 Project Goals

- Learn distributed representations (embeddings) of songs
- Capture musical similarity based on playlist co-occurrence
- Provide a clean, reproducible ML project structure
- Publish work publicly on GitHub without heavy local computation

---

## 📊 Dataset

The project uses a publicly available playlist dataset.

### Playlist Data
Source: https://storage.googleapis.com/maps-premium/dataset/yes_complete/train.txt

- Each line represents a playlist
- Songs are represented by unique IDs
- First two lines contain metadata and are skipped
- Playlists with fewer than two songs are removed

### Song Metadata
Source: https://storage.googleapis.com/maps-premium/dataset/yes_complete/song_hash.txt


Fields:
- `id` – unique song identifier
- `title` – song title
- `artist` – artist name

No authentication is required to access the data.

---
