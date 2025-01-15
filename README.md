# Custom Search Engine with Image Analysis

## Overview
This project develops a **Custom Search Engine** using the Google Custom Search that retrieves websites and images based on a user query. It further processes the images by extracting OCR, using a pretrained model for image detection, generating captions, and calculating similarity scores between the generated captions and responses from the Gemini API.

## Features
- **Google Custom Search Integration**: Retrieves websites and images based on user input.
- **Image Classification**: Classifies images using a pretrained ResNet model.
- **Image Captioning**: Generates captions for images using the BLIP model.
- **Similarity Scoring**: Compares the generated image captions with responses using cosine similarity.
- **Gemini API Integration**: Enhances the search and processing experience by generating context-based responses for user queries.
