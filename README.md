# End-to-end-Masked-Language-Modeling-with-BERT
When training a language model in a self-supervised environment (without human-annotated labels), mask language modeling is an excellent method. An array of supervised natural language processing tasks can then be achieved by fine-tuning such a model.
This example shows you how to start from zero when creating a BERT model, train it on the masked language modeling problem, and then refine it further on a sentiment classification task.
We will use the Keras TextVectorization and MultiHeadAttention layers to create a BERT Transformer-Encoder network architecture.
