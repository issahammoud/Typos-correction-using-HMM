# Typos-correction-using-HMM

This school project aims to calculate the most probable sequence of characters using Hidden Markov Model and Viterbi algorithm in order to correct typos. 
In addition, there is a comparison between using a first order and a second order HMM. 

# About the data

Data for this problem was generated as follows: starting with a text document, in this case, the Unabomber's Manifesto, all numbers and punctuation were converted to white space and all letters converted to lower case. The remaining text is a sequence only over the lower case letters and the space character, represented in the data files by an underscore character. Next, typos were artificially added to the data as follows: with 90% probability, the correct letter is transcribed, but with 10% probability, a randomly chosen neighbor (on an ordinary physical keyboard) of the letter is transcribed instead. Space characters are always transcribed correctly. In a harder variant of the problem, the rate of errors is increased to 20%.

The datasets is represented in 4 pickles: train10 and test10 constitute the dataset with 10% or spelling errors, while train20 and test20 the one with 20% or errors.
