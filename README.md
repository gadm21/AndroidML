# AndroidML
Running onnx-optimized text-to-speech models, language models, and speech-to-text models on android



## Introduction
This repository contains the code for running onnx-optimized text-to-speech models, language models, and speech-to-text models on android. The code is based on the [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) framework. 

## Structure
### SherpaOnnxTts
This module contains the code for running onnx tts models on android.
The models are located in `app/src/main/assets`. There are two models located in two folders: `vits-ljs` and `vits-vctk`. 

## Usage
1. Clone the repository using the command `git clone https://github.com/k2-fsa/AndroidML.git`.
2. Navigate to the project directory using `cd AndroidML`.
3. Open the `README.md` file located in the root directory.
4. Scroll down to the "Structure" section.
5. In the `app/src/main/java/com/k2fsa/sherpa/onnx/MainActivity.kt` file, change the `modelDir`, `modelName`, and `lexicon` variables according to the model you want to use. For example, to use the `vits-ljs` model, set the `modelDir` variable to `vits-ljs`, the `modelName` variable to `vits-ljs.onnx`, and the `lexicon` variable to `lexicon.txt`.