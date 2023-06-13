# StyleGAN_CLIP
This project offers an implementation of StyleGAN 2 and 3 with CLIP. StyleGAN_CLIP uses technique for manipulating images by leveraging textual descriptions. By merging the generative potential of a pretrained StyleGAN generator with the visual-language capabilities of CLIP, StyleCLIP empowers users to produce visually captivating images guided by text inputs.

## Installation
Go to the project path and follow the instructions:
 - ``` git clone https://github.com/NVlabs/stylegan3 ```
 - ``` git clone https://github.com/openai/CLIP ```
 - ``` pip install -e ./CLIP ```
 - ``` pip install einops ninja ```
 - ``` pip install -r requirements.txt ```
 - for other dependency check https://github.com/ouhenio/StyleGAN3-CLIP-notebooks
## Usage
This project is specifically designed and tested with the StyleGAN2 pretrained model from the StyleGAN3 repository.
- Download the pretrained StyleGAN2 model (in .pkl format) from the StyleGAN3 repository or use a custom one.
- Move the downloaded .pkl file to the main path of the StyleGAN_CLIP implementation.
- Update the name of the model file in the code to match the newly placed .pkl file and adjust parameters.
- Run with
```.bash
python main.py
 ```
## References
1. [StyleGAN3CLIP](https://github.com/ouhenio/StyleGAN3-CLIP-notebooks), from Ouhenio
2. [stylegan3](https://github.com/NVlabs/stylegan3/tree/main), from NVlabs
3. [CLIP](https://github.com/openai/CLIP), from OpenAI 

