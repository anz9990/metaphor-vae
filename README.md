# metaphor-vae

Interpolating Metaphors with Variational Autoencoders

# Dependencies

* Python 3.6
* Pytorch 0.4.1
* Fastai 0.7


# Installation

1. Create a conda environment:
   ```
   conda env create -n metaphors python=3.6
   ```
2. Install dependencies
   ```  
   pip install fastai==0.7.0 torchtext==0.2.3 opencv-python spacy
   sudo apt update && sudo apt install -y libsm6 libxext6
   ```
3. Install Spacy `en` model:
   ```
   python -m spacy download en
   ```
4. Install Pytorch `0.4.1` (default version of pytorch with fastai 0.7.0 is 0.3.0):
   ```
   pip install torch==0.4.1
   ```
   
# Data

The data was originally scraped from
http://metaphors.iath.virginia.edu/metaphors and is licensed under [CC BY-NC-SA
4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Troubleshooting
* https://stackoverflow.com/questions/47113029/importerror-libsm-so-6-cannot-open-shared-object-file-no-such-file-or-directo
* https://github.com/OpenNMT/OpenNMT-py/issues/900#issuecomment-437919442
* https://forums.fast.ai/t/fastai-v0-7-install-issues-thread/24652
