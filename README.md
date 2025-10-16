# GameSense AI

## Overview
GameSense AI is an intelligent gaming personality analyzer that uses a pre-trained **DistilBERT** model from **Hugging Face**. It analyzes a gamer’s chat or command style and predicts their **game personality type** — like *Aggro Catalyst*, *Tactical Architect*, *Synergy Core*, or *Apex Solo*.  
This project helps players and teams understand their gameplay behavior for better strategy and coordination.

## Motivation
Understanding player behavior can improve team coordination and enhance gaming strategies. Many games rely on text communication, and GameSense AI turns these messages into actionable insights by predicting personality types from text commands.

## Features
- Classifies gaming text into 4 distinct personality types
- Provides confidence scores for each prediction
- Interactive mode for real-time analysis
- Built with **PyTorch** and **Transformers**
- Ready for fine-tuning on custom gaming datasets

## Model Architecture
- **Base Model:** DistilBERT (lightweight, fast variant of BERT)  
- **Number of Labels:** 4 (AGGRO CATALYST, TACTICAL ARCHITECT, SYNERGY CORE, APEX SOLO)  
- **Input:** Gaming chat text  
- **Output:** Predicted personality type with confidence score  

## Dataset
- Sample dataset is included as lists in the script for demonstration purposes.  
- Custom datasets can be created from game chat logs or team communication.  
- For production-level performance, a large labeled dataset is recommended for fine-tuning.

## Installation
1. Clone this repository:  
```bash
git clone <repo_url>
cd GameSense-AI
