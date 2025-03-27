# mygpt

A lightweight, experimental GPT-style model called myGPT was created specifically for
producing Malayalam text. myGPT is an enjoyable side project that aims to explore
language modeling with a compact and flexible approach, in contrast to state-of-theart transformer models developed for research or commercial uses. It is similar to
early GPT models in that it emphasizes effective small-scale training over large-scale
implementation.

So you can train the default tiny 15M parameter model, and use that in your projects instead of ChatGPT.

## Setup

pip install -r requirements.txt

## Using it

Run main.py for training a 15M English GPT, although it's not very configurable. What you're looking for is at the bottom of this readme.

### Training

Uncomment "train()" in main.py / main_mal.py. It will save checkpoints of the model parameters into the CWD.

### Inference / text generation

Once you have trained the model, comment "train()" and uncomment "inference()". Setup whatever prompt you want. Then run the script to see the generated text appear.
