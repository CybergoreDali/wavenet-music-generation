# wavenet-music-generation

Attempt to generate music with different implementations of the wavenet model.
So far, I was only able to generate noise/silence with it.

To reproduce, launch the google colab instance linked at the top of the .ipynb-file.
Upload at least 20 audio files to /contents/mp3 (the files don't have to be in the mp3 format) or specify the link to the audio files in the corresponding code block.
For the tensorflow 2 implementation, it is necessary to upload an audio file and convert it with the corresponding code block. It will be automatically saved as  /contents/input.wav.

Run the remaining commands to automatically generate mono-channel wave files at a 16kHz sampling rate from the uploaded audio files, split them into training and test files, train the model with it and generate audio from the trained model.


Worked on as part of the Machine Learning Elective at Hochschule Darmstadt with the kind support of Meghan Kane.
