# HypeWave: Real-Time Stream Analytics and Automated Highlight Clipping

**Data Mining Lab - Project Report**
Chandigarh University - Bachelor of Computer Applications (5th Semester, 2026)

| Name   | UID        |
|--------|------------|
| Gautam | 24BCA10086 |
| Harjas | 24BCA10084 |
| Arushi | 24BCA10078 |

**Subject:** Data Mining Lab  **Submitted to:** Ms Jyoti

## About the project
HypeWave finds the most exciting moments of a livestream by reading its live chat instead of the video.
Chat messages are grouped into 10-second windows, and four features are measured in each window:
message velocity, emoji density, capital-letter intensity and hype-word rate. A z-score against a
lagged rolling baseline, SciPy peak detection and a velocity-ratio gate pick out real spikes, and each
peak is turned into a short highlight clip with FFmpeg / MoviePy. A Streamlit dashboard shows why
every highlight was chosen.

On a synthetic test stream with four planted hype moments it found all four with no false positives,
and all eight automated tests pass.

## Files
- `HypeWave Real-Time Stream Analytics and Automated Highlight Clipping.pdf` - full project report

**Tools used:** Python, pandas, NumPy, SciPy, pytchat, FFmpeg, MoviePy, Streamlit, Altair
