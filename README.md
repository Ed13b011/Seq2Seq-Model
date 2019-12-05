# Seq2Seq-Model

Neural machine translation models are often based on the seq2seq architecture. The seq2seq architecture is an encoder-decoder architecture which consists of two LSTM networks: the encoder LSTM and the decoder LSTM. The input(English sentences in our case) to the encoder LSTM is the sentence in the original language; the input to the decoder LSTM is the sentence in the translated language(French sentences) with a start-of-sentence token. The output is the actual target sentence with an end-of-sentence token.

The idea is to use one LSTM to read the input sequence, one time-step at a time, to obtain large fixed-dimensional vector representation, and then to use anotherLSTM to extract the output sequence from that vector
