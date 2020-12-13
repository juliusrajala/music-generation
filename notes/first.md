# First notes

[Source post](https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/)

## Background

Music is essentially composed of Notes and Chords. Let me explain these terms from the perspective of the piano instrument:

- Note: The sound produced by a single key is called a note
- Chords: The sound produced by 2 or more keys simultaneously is called a chord. Generally, most chords contain at least 3 key sounds
- Octave: A repeated pattern is called an octave. Each octave contains 7 white and 5 black keys


## Approaches

- Two deep learning based architectures.
  - Wavenet
  - LSTM

Deep learning is a field of Machine Learning which is inspired by a neural structure. These networks extract the features automatically from the dataset and are capable of learning any non-linear function.
- Universal Functional Approximators.

### WaveNet

- Deep learning based generative model for raw audio developed by Google DeepMind.
- Wavenet is like a language model from NLP.
  - In a language model, given a sequence of words, the model tries to predict the next word. Similar to a language model, in WaveNet, given a sequence of Samples, it tries to predict the next sample.