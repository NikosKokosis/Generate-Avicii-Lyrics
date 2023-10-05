# AI-Powered Music Composition with LSTM Neural Networks

## Project Overview

Welcome to the AI-Powered Music Composition project! In this creative endeavor, we harness the magic of Long Short-Term Memory (LSTM) Neural Networks to generate original music lyrics inspired by the legendary artist Avicii. This project takes you on a journey through the fusion of AI and music, exploring the boundaries of lyrical creativity.

## Data Source

- **Corpus**: [Avicii Lyrics](avicii_lyrics.txt)

## Project Highlights

Here's an overview of the key aspects of our music composition project:

- **Character Mapping**: We dive into the process of mapping characters to numerical indices, a crucial step in enabling our LSTM model to understand and generate text creatively. This mapping forms the foundation of our lyrical journey with AI.

- **Data Preparation**: We take raw text data and prepare it for the LSTM model. One-hot encoding is used to convert sequences and labels into a format that the model can comprehend, bringing the text to life within the neural network.

- **Model Training**: Our LSTM model undergoes intensive training, with two distinct sessions—12 epochs and 25 epochs. We analyze the results and the creative output that emerges from the neural network.

- **Lyric Generation**: We explore the generated lyrics and examine how well the model captures the essence of Avicii's lyrical style. While the output showcases glimpses of poetic brilliance, we also observe its limitations in achieving consistent storytelling.

## Project Structure

The project is organized into several sections, each corresponding to the project highlights mentioned above. You can explore each section in detail within the provided [Jupyter Notebook](avicii_lyrics_composer.ipynb).

## Usage

To delve into the world of AI-powered music composition, simply navigate to the relevant sections within the Jupyter Notebook and execute the code cells.

## Conclusions

Our AI-Powered Music Composition project offers a tantalizing glimpse into the synergy of AI and artistic expression. While the model successfully captures elements of Avicii's style, it also highlights the irreplaceable role of human creativity in music composition. The journey continues, with infinite possibilities awaiting exploration.

## Model Weights

You can find the trained model weights for your own use:

- [Model Weights (12 Epochs)](model_weights_12epochs.h5)
- [Model Weights (25 Epochs)](model_weights_25epochs.h5)

## Dependencies

The project relies on Python libraries for deep learning and text processing. Please ensure you have the necessary libraries installed, as specified in the project notebook.