# AudioSet Tutorial

This repository will contain notebooks and code snippets for working with [Google AudioSet](https://research.google.com/audioset/), a large-scale dataset of
manually annotated audio events.

`tutorial_reading_audioset_tfrecords.ipynb` explains how to open a TFRecord that contains AudioSet feature vectors (embeddings), video IDs and labels.

# About AudioSet
AudioSet consists of an expanding ontology of 632 audio event classes and a collection of 2,084,320 human-labeled 10-second sound clips drawn from YouTube videos. The ontology is specified as a hierarchical graph of event categories, covering a wide range of human and animal sounds, musical instruments and genres, and common everyday environmental sounds.

Instead of raw audio, every example is made available as a sequence of 128-dimension embeddings (one embedding for every second of audio). The embeddings were obtained after passing the log-scaled mel-spectrograms of the audio waveform through a deep convolutional neural network trained on millions of audio clips (_VGGish_).

# Where to find further information
Creators/users of the dataset can be found at [audioset-users](https://groups.google.com/forum/#!forum/audioset-users).

 


