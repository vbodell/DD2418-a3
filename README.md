# DD2418 A3
Implementation of a viterbi algorithm on bigram and trigram word processing.
## 1
### (a) Explain how this model of keystroke errors can be cast as a Hidden Markov Model.
Which are the hidden states, the observations, the state transition probabilities,
and the observation probabilities?

The hidden state is the intended letter, the observations are the letters seen, which may be the actual letter or a neighbouring letter. The state transition probabilities is the likelihood of a certain letter following another given letter. Observation probabilities is the likelihood of seeing a certain letter given the intended letter/hidden state.

### (b) The ViterbiBigramDecoder program contains a code skeleton for applying the Viterbi
algorithm to the text correction problem, making the text more legible. Extend the code
so that it works correctly (look for the comments YOUR CODE HERE and REPLACE THE
STATEMENT BELOW WITH YOUR CODE in the program). Try your implementation on some
test cases by running the script run bigram decoder.sh. You may compare with the
expected results in the file test bigram decoding.txt and/or by using the --check
flag.
Hint: Note that the program adds a START END symbol at the end of the input string.
To recover the result, your implementation can simply follow the backpointers from the
START END state in the final time step.

## 2
### (a) Implement the Viterbi algorithm using trigram probabilities by extending the class
ViterbiTrigramDecoder, so that it works correctly. Try your implementation on the
test cases by running the script run trigram decoder.sh, and compare with the expected
results in the file test trigram decoding.txt, and/or by using the --check
flag.
### (b) Run your bigram and trigram decoders on the 5 files mistyped 1.txt to mistyped 5.txt.
Report the output of the two programs.
### (c) What are the topics of these five texts? Can you identify (or guess) the sources?
