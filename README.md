# NLP_Assignments
NLP Unibo AI assignments 2021/22

## 1st Assignment abstract
We tackled the POS-tagging with neural networks, working on a limited amount
of data and trying different kind of structures. We chose to output a one-hot
encoding of the class and used a single fixed matrix for the embedding layer.
The OOV words have been mapped into a random vector, then we trained and
conducted a validation step after each epoch. After this we evaluated the model
on training data and looked at the outputs.

## 2nd Assignment abstract
We tackled the problem of Fact Checking using the FEVER dataset. We decided
to create a Model that would take as input two embedding vectors, one for the
claim and one for the corresponding evidence, merge them together and output
the result (support, refutes) in one-hot encoding format. We tried different
models suggested, but the one that produced the better results was the MLP.
It consists in a dense layer applied before the merging of the two vector and
after a reshape layer. On this model we tried the three merging strategies and
evaluate the results with the Multi-input classification and the Claim verification evaluation.
