# NOTE: Implementation hidden due to Coursera Terms of Service.

# Jazz Improvisation with LSTM

Generating Jazz music with a [Long-Short-Term-Memory (LSTM)](https://en.wikipedia.org/wiki/Long_short-term_memory) using Keras.

# Implementation  
Music has been pre-processed to render into musical values. The RNN model will train on the dataset to generate a sequence of musical values that are post-processed into midi music. The post-processing ensures the same sound isn't repeated too many times, two notes aren't far part in pitch, etc.  
  
# Lessons Learned
1. A sequence model can be used to generate musical values, which are then post-processed into midi music.  
2. Fairly similar models can be used to generate dinosaur names or to generate music, with the major difference being the input fed to the model.  
3. In Keras, sequence generation involves defining layers with shared weights, which are then repeated for the different time steps 1, ..., T_x.  

# Credit:
[Sequence Models Course for Deep Learning Specialization](https://www.coursera.org/learn/nlp-sequence-models)
