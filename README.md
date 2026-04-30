# GAIA Final Agent

This repository documents my final project for the Hugging Face Agents Course.

I built and submitted an AI agent evaluated on a subset of the GAIA benchmark, achieving a final score of **100% (20/20 correct answers)**.

## Project Overview

The goal of this project was to build an agent capable of answering real-world benchmark questions that require reasoning, tool use, file analysis, audio transcription, spreadsheet processing, and exact answer formatting.

The final assignment used a scoring API that evaluated answers using exact matching, which made formatting and validation especially important.

## Final Result

- **Score:** 100%
- **Correct answers:** 20/20
- **Benchmark:** GAIA subset
- **Course:** Hugging Face Agents Course

## Tools and Technologies

- Python
- Hugging Face Spaces
- Google Colab
- Gradio
- pandas
- Whisper
- Hugging Face Datasets
- requests

## Key Work

During the project, I worked on:

- Setting up Hugging Face authentication and secrets
- Accessing gated GAIA dataset files
- Processing Excel spreadsheets with pandas
- Transcribing audio files with Whisper
- Solving logic and table-based questions
- Cleaning answers for exact-match evaluation
- Submitting final answers through the course scoring API

## What I Learned

This project taught me that building reliable AI agents requires more than prompting. It also requires debugging, tool use, structured workflows, file handling, local validation, and careful answer formatting.

## Links

- Hugging Face Space: https://huggingface.co/spaces/nuha-alharbi10/gaia-final-agent
- Source Code on Hugging Face: https://huggingface.co/spaces/nuha-alharbi10/gaia-final-agent/tree/main
- Final Score: 100% - 20/20
