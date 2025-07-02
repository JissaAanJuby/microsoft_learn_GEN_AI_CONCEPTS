# microsoft_learn_GEN_AI_CONCEPTS

# Generative AI
      capability of ai to generate create original content.
      1  natural language generation
      2  image generation
      3  code generation

# how models work
      1 Tokenization 
            words into tokens and tokens into numbers
            tokens of good value are taken into use
      2 word embeddings
            tokens are turned into vectors 
            shows the semantic relationship of words that is how similar the angle of lines is
            semantically similar tokens should result in vectors that have a similar orientation
            dog and puppy similar vectors
      3 architectural developments
            Words can differ in their meaning depending on the context
            Recurrent Neural Networks (RNNs).
            a sentence each word is a input each input has a output part and a hidden part the hidden part stores the prev output finally all the outpyts mixed in the hidden part is called mask and mask is given as an input to get a output like predicting a new word in autocomplete
#challenge:
    An RNN however, includes all (relevant and irrelevant) information in a hidden state. As a result, the relevant information may become a weak signal in the hidden state, meaning that it can be overlooked because there's too much other irrelevant information influencing the model.
