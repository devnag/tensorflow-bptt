A Simple Design Pattern for TensorFlow Recurrency
===============


### Introduction
This repo includes the bptt.py library for recurrent graph bookkeeping (in Tensorflow) and a sample client which learns to predict a simple palindromic sequence using a double-layer LSTM (Graves 2013). 

See https://medium.com/@devnag/ for the relevant blog post.


### Running
Run the sample code by typing:


```
./example_bptt.py
```

...and you'll train a 2-layer LSTM on a palindromic sequence prediction task, then test it on sequential inference. The loss should drop below 1e-3 pretty quickly, and then you'll see the last few hundred attempts vs. the expected output.


 