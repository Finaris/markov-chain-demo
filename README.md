#Markov Chain Demo
A markov chain is a stochastic process which can predict future states of a system given the current state of the same system. In this program, I take an input text file (expected input is some type of raw text which can contain punctuation) and then filter through the text. The text is stored, and then weighted depending on the presence of certain words, and then an algorithm is used to predict the probability of the next word given the previous word in the text chain. The weight can be adjusted depending on how connected the words are desired to be (with smaller values of the variable MAX resulting in more non-sensical chains but greater variety). To read more on the implementation of Markov chain predictive models, see:

https://en.wikipedia.org/wiki/Markov_chain
https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo
