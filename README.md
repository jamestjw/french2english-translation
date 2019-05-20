# Seq2Seq French -> English Translation

We train a seq2seq translation model using the Transformer architecture on the Giga-word French-English parallel corpus. The notebook illustrates the definition of the architecture and how the datablock API is 'modified' to allow a Seq2Seq model (which is not naturally supported by FastAI) to be implemented.
