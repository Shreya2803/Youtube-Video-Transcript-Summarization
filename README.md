# Youtube Video Transcript  & Summarization

YouTube Video Summarizer is a Python project that fetches the transcript of a YouTube video, generates a summary of the transcript using the BART model from the transformers library, and writes the transcribed text and summary to separate PDF files.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)


## Overview

The YouTube Video Summarizer project uses the `youtube_transcript_api` to fetch the transcript of a specified YouTube video. It then employs the `transformers` library, utilizing the BART model, to generate a summary of the transcript. The summarized text and the original transcribed text are written to separate PDF files using the `reportlab` library.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/YouTube-Video-Summarizer.git
   cd YouTube-Video-Summarizer
  


## Usage

1.Replace your 'video_id' here with the actual YouTube video ID in the main.py file.

2. Run the main.py script:
   ```bash
   python main.py
3.The script will fetch the transcript, generate a summary, and save the results in a PDF file: "Summary.pdf" and the whole transcript in "Transcript.pdf".


## Dependencies

  Install the required dependencies:
   ```bash
  pip install transformers youtube_transcript_api reportlab
 

    

