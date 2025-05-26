Used python version is 3.12.10
The requirements.txt file has been shared with all the dependencies.

Use this line to install all dependencies:
pip install -r requirements.txt

OR you can install them manually using:
pip install abuse==0.1.1 ipython==8.27.0 jiwer==3.1.0 librosa==0.11.0 matplotlib==3.9.2 noisereduce==3.0.3 numpy==2.0.2 pandas==2.2.2 pydub==0.25.1 scipy==1.14.1 soundfile==0.13.1 transformers==4.51.2 torch

Steps:
1. Make sure to have noise_tcdvoip folder with all audios in the same directory as the .ipynb
2. The audio_transcribed.csv should also be in the same directory
3. install dependencies.
4. run the notebook.
5. new folders names censored_audio and denoised_audios are created.
6. censored_audio has the abusive words beeped out from the audios.