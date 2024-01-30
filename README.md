# [A Practical OpenAI Whisper Transcription Guide](#a-practical-whisper-transcription-guide)

A beginner's guide to using OpenAI's Whisper, a powerful and free to use transcription/translation model. If you find this guide helpful, please consider smashing that ⭐ button! 😎

Or follow the [TL;DR](#tldr) to get started right away!

## [Description](#description)

This repository contains a practical guide designed to help users, especially those without a technical background, utilize [OpenAI's Whisper](https://openai.com/research/whisper) for speech transcription and translation. We will utilize [Google Colab](https://colab.research.google.com/) to speed up the process via their **free GPU**. The guide includes a step-by-step walkthrough on setting up and executing transcription commands with various options. It's tailored to make the process of speech-to-text conversion accessible and straightforward.

You may also view the accompanying supplamentary tutorial video <a target="_blank" href="https://youtu.be/i4Sgg-ptRzs">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" alt="Tutorial Video" width="24" height="24"/>
</a>

## [How to Use the Notebook](#how-to-use-the-notebook)

The tutorial assumes you have an audio file (mp3, flac, wav, etc.) ready to use in the demonstration. If you don't have one handy, feel free to download the sample audio file provided in this repo [here](AllStar.mp3). 

 1. **Accessing the Notebook**: Open the [Whisper_Tutorial.ipynb](Whisper_Tutorial.ipynb) file and look for the "Open in Colab" badge at the top of the file. You may also click here 
   <a target="_blank" href="https://colab.research.google.com/github/keatonkraiger/Whisper-Transcription-Tutorial/blob/main/Whisper_Tutorial.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
    </a>

 2. **Making a Copy in Colab**: Once the notebook is open in Google Colab, go to the 'File' menu in the Colab toolbar. Select 'Save a copy in Drive' from the dropdown menu. This will create a copy of the notebook in your Google Drive, allowing you to run and edit it without affecting the original version.
 3. **Running the Notebook**: Follow the instructions in the notebook to transcribe your audio file!

## [TL;DR](#tldr)

Assuming you are using the audio file [here](AllStar.mp3) (or a file with the same name): 

1. Open the [Whisper_Tutorial](https://colab.research.google.com/github/keatonkraiger/Whisper-Transcription-Tutorial/blob/main/Whisper_Tutorial.ipynb) in Colab.
2. Enable the GPU (Runtime > Change runtime type > Hardware accelerator > GPU). 
3. Upload the audio file to Colab (click the folder icon on the left, then click the upload icon).
4. Run all the cells in the notebook (Runtime > Run all).
5. Download the zip folder with the transcription files (right-click `transcription.zip` in the file explorer and select "Download").


## [References](#references)

This tutorial just follow's OpenAI's Whisper's official documentation. For more information, please refer to the official documentation [here](https://github.com/openai/whisper).