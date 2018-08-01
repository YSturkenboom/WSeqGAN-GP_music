
## Introduction
This repository contains an implementation of WGAN-GP in SeqGAN for polyphonic music generation.
The accompanying paper can be found [here](#) TODO: upload paper

This repository is a hard fork of [SeqGAN for polyphonic music generation](https://github.com/L0SG/seqgan-music).

## Dependencies
Python 2.7
Tensorflow 1.4 or newer (tested on 1.9)
pip packages: music21, pyyaml, nltk, pathos

## Usage
Use the command `python music_wseqgangp.py`to train the SeqGAN version with WGAN-GP,
or `python music_wseqgan.py` for the SeqGAN version with a regular WGAN.

The default hyperparameters in SeqGAN.yaml are the parameters that have been used in the paper.
5 sample MIDI sequences are automatically generated per epoch.

## Dataset
The model uses a MIDI version of Nottingham database (<http://abc.sourceforge.net/NMD/>) as the dataset.
Preprocessed musical word tokens are included in the "dataset" folder.

