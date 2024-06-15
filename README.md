# Whisper-Even-Tuning

The work on fine-tuning Whisper model on Even ASR datasets.

## Datasets
1. [Even Speech Biblical](https://huggingface.co/datasets/tbkazakova/even_speech_biblical) - collection of high-quality audio recordings of biblical texts. Total ~67 minutes of audio fragments and its transcription.
2. [Even Speech Pakendorf](https://huggingface.co/datasets/tbkazakova/even_speech_pakendorf) - collection of audio recordings of tales, narratives, conversations, phonetic sessions. May have inaccurate markup of fragments. Total ~10 hours of audio fragments and its transcription.

## Notebooks
1. `finetune_whisper_biblical_russian.ipynb` - Notebook (russian notes) with fine-tuning Whisper model on Even Speech Biblical dataset.
2. `finetune_whisper_biblical_english.ipynb` - Notebook (english notes) with fine-tuning Whisper model on Even Speech Biblical dataset.
3. `finetune_whisper_pakendorf.ipynb` - Notebook (english notes) with fine-tuning Whisper model on Even Speech Pakendorf dataset.

Notebooks have further instructions on running the project in Colab or local machine.

## Results
1. On Biblical dataset best WER: 30.27
2. On Pakendorf dataset best WER: 67.99
