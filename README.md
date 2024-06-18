# FishNet: Invasive Fish Species Detection

FishNet is a deep learning project designed to identify invasive fish species in the Mediterranean Sea using video data. This project utilizes a YOLO model trained on a custom dataset created from video footage.

![Detection Demo](Images/DetectionGif.gif)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Real-Time Detection](#real-time-detection)
- [Running the Inference Script](#running-the-inference-script)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Project Overview
FishNet aims to assist in the early detection and monitoring of invasive fish species. The application processes video frames in real-time, identifies different fish species, and alerts relevant stakeholders when invasive species are detected.

## Features
- Real-time fish species detection
- Alerts and notifications for invasive species
- Data logging for further analysis
- User-friendly interface for fishermen and researchers

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FishNet.git
   cd FishNet
   
2. Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the required dependencies:
pip install -r requirements.txt

4. Download the pre-trained YOLO model weights and place them in the weights directory. Download link












