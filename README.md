# Music Generation using GAN

Welcome to the "Music Generation using GAN" project! This guide will walk you through the steps to run the project successfully.

## Project Structure

The project repository contains the following folders and files:

- **Music_GAN**: Contains the code and dataset for the project.
- **Sentiment_Poetry.ipynb**: Used for emotion analysis on poetry, which contributes to music generation.
- **MIDI_Image.ipynb**: Converts MIDI files to images for training data preparation.
- **Music_GAN.ipynb**: Main code file for the GAN-based music generation process.

## Setup and Prerequisites

1. Clone the repository: [GitHub Repository](https://github.com/SarCode/music-generation-using-GAN).
2. Upload the `Music_GAN.ipynb` file to Google Colab.

## Running the Code

Follow these steps to run the main code for music generation:

1. **Upload Dataset**: You can use the original dataset available in the [GitHub Repository](https://github.com/SarCode/music-generation-using-GAN). Optionally, you can upload the dataset to your Google Drive for easy access.

2. **Run Music_GAN.ipynb**:
   - Open the `Music_GAN.ipynb` notebook in Google Colab.
   - Mount your Google Drive if you've uploaded the dataset there.
   - Modify any necessary paths or configurations as mentioned in the notebook.
   - Run the cells step by step to execute the GAN-based music generation process.

## Output and Results

- The output images generated from the MIDI files can be found in the `lofi_png` folder.
- Sample input and output files are stored in the `Final_Output` folder. The input, named "Sample Poem," and the corresponding output `.wav` files are located in the same directory.

## Note

- You do not need to run `Sentiment_Poetry.ipynb` or `MIDI_Image.ipynb` as their outputs are already available.
- The original dataset and additional resources are available in the [GitHub Repository](https://github.com/SarCode/music-generation-using-GAN).

Enjoy exploring the world of music generation using GANs!
