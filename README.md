# Sora 2 Video Enhancement Tool

![License](https://img.shields.io/badge/license-GPLv3-green.svg?style=flat)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20MacOS%20%7C%20Linux-lightgrey.svg)

## Overview

A Python-based video processing solution for cleaning up and enhancing Sora 2 AI-generated content. This tool uses advanced inpainting algorithms to restore video frames and improve visual quality.

## Key Features

- 🎬 Intelligent frame-by-frame video analysis
- 🖼️ AI-powered inpainting for visual restoration
- ⚡ Optimized processing pipeline
- 🌐 Web-based user interface
- 📁 Batch processing support

## How It Works

The application analyzes each video frame using computer vision techniques. When processing is initiated, the system applies inpainting algorithms to restore and enhance the visual content. The processed video is then rendered and made available for download.

## System Requirements

| Component | Requirement |
|-----------|-------------|
| Python | 3.10 or higher |
| OS | Windows / MacOS / Linux |
| RAM | Minimum 4GB |
| Dependencies | [FFmpeg](https://ffmpeg.org/download.html) |

## Installation

Clone the repository using Git:
```bash
git clone https://github.com/tbjrns/sora2-watermark-remover
```

Install the required dependencies:
```bash
cd sora2-watermark-remover
pip install requirements.txt
```

## Usage

### Desktop Application

Launch the main application:
```bash
python main.py
```

This opens a web interface in your browser where you can upload and process your videos. Processed files are saved to the `output` folder.

### Web Server Mode

For integration with other projects, run the server version:
```bash
python server.py
```

The API server starts on port 8000, ready for programmatic access.

## API Documentation

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/upload` | POST | Submit video for processing |
| `/status` | GET | Check processing status |
| `/download` | GET | Retrieve processed video |

## Support the Project

If you find this tool helpful, consider supporting continued development:

| Currency | Address |
|----------|---------|
| BTC | `bc1q8grhtxdw37npcdadm7xa848vquqgurj9ecvpex` |
| ERC20 | `0x2d19c72fb8b3a7cdc7fa4970b5c777966f547854` |

**Thank you for your support! 🙏**

## License

This project is licensed under GPLv3 - see the LICENSE file for details.
