# Master's Thesis Project

Author: Oskar Ekestorm

This repository contains files relating to my Master's Thesis for easy access.

The NMT model was trained using [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py).

The game text from *[Persona 5 Royal](https://en.wikipedia.org/wiki/Persona_5)* was used as analysis data.


## Configuration File

[`config.yaml`](/config.yaml) is the configration file I used when trainign my NMT model using OpenNMT.


## Game Data — Corpus

[`game-data`](/game-data.csv) shows the amount of bitexts collected from each game used to form the corpus for my study.

In total, 767.4k bitexts were used, of which 625k bitexts where used for training the NMT model.


## Translation Quality Assessment Model

[`tqa-model.csv`](/tqa-model.csv) is my TQA model provided as a `.csv` file for easy access.


## Examples

[`examples.csv`](/examples.csv) contains all examples used in my thesis. The file provides

- Example number as presented in the thesis
- The Japanese original
- The official English translation
- The translation provided by my NMT model
- A translation provided by Google Translate
- A translation provided by DeepL

The Google Translate and DeepL translations were conducted on `2025-05-22` through their respective official free APIs.
