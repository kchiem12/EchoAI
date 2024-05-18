# EchoAI: Classical Music Generation with LSTM Networks

## Project Overview
EchoAI aims to explore the creative potential of AI in music generation by employing sequence models like LSTM networks to produce original classical music compositions.

## Application Setting
The project generates classical music tracks using machine learning approaches. The original compositions are outputted as MIDI files.

## Repository Contents
- `.gitignore`: Standard gitignore file to exclude unnecessary files from version control.
- `Basic_LSTM.mp3`: The final music output generated by the basic LSTM model.
- `EchoAI_LSTM.ipynb`: Jupyter notebook for preprocessing data, training the basic LSTM model, and outputting MIDI files.
- `EchoAI_LSTM_LocalAttention.ipynb`: Jupyter notebook for training the LSTM model with local attention and outputting MIDI files.
- `Local_Attention_LSTM.mp3`: The final music output generated by the LSTM model with local attention.

## Project Structure

### EchoAI_LSTM.ipynb
This notebook includes:
- Preprocessing of MIDI data.
- Training of the basic LSTM model.
- Generation and output of MIDI files.

### EchoAI_LSTM_LocalAttention.ipynb
This notebook includes:
- Training of the LSTM model with local attention.
- Generation and output of MIDI files.

## How to Run
1. Clone the repository.
2. Open the Jupyter notebooks (`EchoAI_LSTM.ipynb` and `EchoAI_LSTM_LocalAttention.ipynb`) in your preferred environment (e.g., Google Colab).
3. Follow the instructions in the notebooks to preprocess data, train the models, and generate MIDI files, replacing the path to your data, output paths, etc. with your desired paths.

Zips to the trained models can be found here: https://drive.google.com/file/d/1yfJKGeCgyNKW6P8-QoUC0gBN5ptKBaC_/view?usp=sharing2

The link to the original raw MIDI dataset can be found here: https://magenta.tensorflow.org/datasets/maestro

## References
Hawthorne, C., Stasyuk, A., Roberts, A., Simon, I., Huang, C.-Z. A., Dieleman, S., Elsen, E., Engel, J., & Eck, D. (2019). Enabling factorized piano music modeling and generation with the MAESTRO dataset. arXiv. https://arxiv.org/abs/1810.12247

Shen, C., Yao, V. Z., & Liu, Y. (2023, June). Everybody compose: Deep beats to music. In Proceedings of the 14th ACM Multimedia Systems Conference (MMSys '23). ACM. https://doi.org/10.1145/3587819.3592542
