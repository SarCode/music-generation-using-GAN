Hey, 

Here are the instructions to run my project Music Generation using GAN.

Folder Music_GAN contains all the code and dataset.

Code folder contains three files:
1. Sentiment_Poetry.ipynb : Used for emotion analysis on poetry which will be used to generate music.

2. MIDI_Image.ipynb : Used to convert MIDI to Image so that we pass pixels as training data to GAN.

3. Music_GAN.ipynb : This is our main code file which contains all of GAN code.

We don't need to run file 1 and file 2, as their output is already stored.

Original dataset can be found in : https://github.com/SarCode/music-generation-using-GAN

After passing lofi_original(available in URL given above) to MIDI_Image.ipynb, the output images are stored in lofi_png folder.

After running all the code a sample input and output are stored Final_Output folder, where file "Sample Poem" was the input and the output .wav files are stored in the same directory.


Steps to run main code:

1. You can upload dataset(https://github.com/SarCode/music-generation-using-GAN) on Google Drive.
2. Upload Music_GAN.ipynb to Google Colab.
3. Run Music_GAN.ipynb

