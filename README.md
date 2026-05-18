# Rabin Bhatta

### Music producer transitioning into AI music technology for the music industry

I am a seasoned music producer now building AI tools for musicians and music industry professionals. The goal is to make useful systems that reduce manual work, improve creative workflow, and help people make better decisions with audio. My background comes from real music production, with over 60M Spotify streams and 3B+ TikTok views. I am now adding technical depth through an MSc in Sound and Music Computing at Queen Mary University of London.

<p>
  <a href="#featured-projects"><img src="https://img.shields.io/badge/Featured%20Projects-111827?style=for-the-badge" alt="Featured Projects"></a>
  <a href="#music-informatics"><img src="https://img.shields.io/badge/Music%20Informatics-0f766e?style=for-the-badge" alt="Music Informatics"></a>
  <a href="#deep-learning-for-music"><img src="https://img.shields.io/badge/Deep%20Learning%20for%20Music-b91c1c?style=for-the-badge" alt="Deep Learning for Music"></a>
  <a href="#skills"><img src="https://img.shields.io/badge/Skills-1d4ed8?style=for-the-badge" alt="Skills"></a>
  <a href="#connect"><img src="https://img.shields.io/badge/Connect-374151?style=for-the-badge" alt="Connect"></a>
</p>

---

## Featured Projects

| Project | Focus | Stack |
| --- | --- | --- |
| [Audio Identification](https://github.com/RabinBhattaCode/Audio-identification) | A rule based audio fingerprinting system. It turns recordings into spectral peaks, landmark hashes, and offset votes so a short query can be matched to the correct track. | Python, librosa, NumPy, SciPy, scikit-image |
| [Beat Tracking For Ballroom Dance Music](https://github.com/RabinBhattaCode/Beat-Tracking-For-Ballroom-Dance-Music) | A beat and downbeat tracking system. It uses spectral flux, onset detection, tempo estimation, beat tracking, and a simple meter rule for ballroom music. | Python, librosa, mir_eval, NumPy, Matplotlib |
| [Remix Maker using U-Net Separation and AST Classification](https://github.com/RabinBhattaCode/Remix-Maker/tree/main/Remix_Maker_using_U_Net_Separation_and_AST_Classification) | A drum replacement prototype. It separates drum content with a U-Net model, chooses replacement loops with AST classification, and tests the result through notebooks. | Python, PyTorch, audio ML, Jupyter |
| [YouTube Transcript Extractor](https://github.com/RabinBhattaCode/YouTube-Transcript-Extractor) | A local workflow tool for extracting YouTube transcripts and exporting them into useful research or planning formats. | Python, Flask, yt-dlp, HTML/CSS |
| [Ifuno Website](https://github.com/RabinBhattaCode/WTM-BLOG) | A public website project connected to my wider music and media work. | Web development, frontend, deployment |

## Music Informatics

### Audio Identification

This system converts audio into a searchable fingerprint database. The input audio is loaded, converted into an STFT spectrogram, reduced to spectral peaks, and stored as landmark hashes. This is useful because a short query clip can then be matched against a database by repeated offset voting.

The evaluation uses ranking metrics such as Top-1, Top-3, and MAP@3. These metrics show whether the correct track is returned at the top of the search results.

### Beat Tracking For Ballroom Dance Music

This system finds beat times and downbeat times in ballroom dance recordings. It starts by building a spectral-flux onset detection function. Then it estimates tempo, tracks the beat positions, and applies a simple meter rule for downbeats.

This matters because timing is one of the basic things musicians and producers need from audio tools. A beat tracker can support editing, remixing, synchronisation, and music analysis.

## Deep Learning For Music

### Remix Maker using U-Net Separation and AST Classification

This project tests a practical drum replacement pipeline. The separator first tries to isolate drum content from the input audio. Then the classifier selects a replacement loop, and the demo notebook puts the new drum part back into the remix.

The system is a prototype, not a finished product. This is useful because it shows how source separation and classification can support creative workflows for producers.

## Workflow Tools

### YouTube Transcript Extractor

This tool runs locally in the browser and extracts transcripts from YouTube videos. The output can be exported into Markdown, text, CSV, or ZIP files. This is useful for research, content review, planning, and turning long videos into notes that are easier to search.

The project fits my wider goal because music and media professionals spend a lot of time collecting information before making creative decisions. A small workflow tool can reduce that manual work.

## Skills

### Programming and ML

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)](https://scipy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

### Audio, MIR, and DSP

[![librosa](https://img.shields.io/badge/librosa-111827?style=for-the-badge)](https://librosa.org/)
[![Music Information Retrieval](https://img.shields.io/badge/Music%20Information%20Retrieval-0f766e?style=for-the-badge)](https://musicinformationretrieval.com/)
[![Signal Processing](https://img.shields.io/badge/Signal%20Processing-1d4ed8?style=for-the-badge)](https://scipy-lectures.org/intro/scipy/auto_examples/plot_fftpack.html)
[![Source Separation](https://img.shields.io/badge/Source%20Separation-b91c1c?style=for-the-badge)](https://sigsep.github.io/)
[![Beat Tracking](https://img.shields.io/badge/Beat%20Tracking-7c3aed?style=for-the-badge)](https://librosa.org/doc/latest/generated/librosa.beat.beat_track.html)

### Creative AI and Production

[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/claude)
[![ComfyUI](https://img.shields.io/badge/ComfyUI-5956E9?style=for-the-badge)](https://www.comfy.org/)
[![FL Studio](https://img.shields.io/badge/FL%20Studio-FF6A00?style=for-the-badge)](https://www.image-line.com/fl-studio/)
[![Logic Pro](https://img.shields.io/badge/Logic%20Pro-000000?style=for-the-badge&logo=apple&logoColor=white)](https://www.apple.com/logic-pro/)

### Web and Tools

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Frontend](https://img.shields.io/badge/Frontend-2563eb?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer)

## Current Focus

- Building AI tools that help musicians and music industry professionals work faster.
- Applying Music Information Retrieval methods to real studio and catalogue problems.
- Exploring source separation, classification, remix generation, and audio search.
- Turning academic audio methods into practical tools that producers can actually use.

## Connect

[![Website](https://img.shields.io/badge/Wadiz%20This%20Music-111827?style=for-the-badge)](https://wadizthismusic.com)
[![GitHub](https://img.shields.io/badge/GitHub-RabinBhattaCode-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RabinBhattaCode?tab=repositories)
[![YouTube](https://img.shields.io/badge/YouTube-katmandusounds-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@katmandusounds)
[![TikTok](https://img.shields.io/badge/TikTok-katmandusounds-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@katmandusounds)
[![Produced by katmandusounds](https://img.shields.io/badge/Spotify-Produced%20by%20katmandusounds-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/playlist/6ZDiTpfDayBYwdzuFw7axg)
[![Spotify](https://img.shields.io/badge/Spotify-Katmandu%20Sound-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/artist/1255i2Jr7gEHyppuqmnsm5)
[![Spotify](https://img.shields.io/badge/Spotify-Artist%20Profile-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/artist/10ks8LfDCLyOb7gE1YhxPE)

---

Studio experience, academic research, and AI implementation for practical music industry tools.
