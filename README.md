# Rare-words-in-text-summarization.
# Pointer-Generator-Pytorch

## About
The pytorch implementation of [Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/abs/1704.04368). 
This implementation also tries to use Transformer as the encoder.

## Requirements
* python==3.7.4
* pytorch==1.4.0
* pyrouge==0.1.3
* tensorflow>=1.13.1

## Quick start
* The path and parameters of project:
you might need to change some path and parameters in utils/config.py according your setup.
* Dataset:
you can download the CNN/DailyMail dataset from https://github.com/JafferWilson/Process-Data-of-CNN-DailyMail, 
then run make-datafiles.py to process data. For the specific process, you can refer to https://github.com/abisee/cnn-dailymail.
* Run: 
you can run train.py, eval.py, and test for training, evaluating, and test, respectively.

### Note:
* There is only single example repeated across the batch in the decode mode of beam search.


# Abstractive Text Summarization with Word Frequency Information

## Overview

This project is based on the article "Improving Abstractive Text Summarization with Word Frequency Information." It focuses on enhancing abstractive text summarization using machine learning techniques and incorporating word frequency information.


## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sanygit/Suvidha-foundation-intern-Rare-words-in-text-summarization.git
