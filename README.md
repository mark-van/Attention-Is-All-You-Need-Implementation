# Abstract


Transformers are a type of deep-learning model that has gained notoriety for often
being the best model for language processing and computer vision tasks. This
paper presents an implementation of the original transformer model from the
2017 paper Attention Is All You Need [1] with an emphasis on creating easily
digestible code and explanations. With readability being prioritized over efficiency,
the corresponding Jupyter Notebook of my model provides a new perspective
on how transformer model code can be written and contributes to the expanding
transformer learning community. On the Multi30k [7] English-German dataset
the model received a BLEU score of 36.56 after being trained on Google Colab
with Nvidia’s T4 GPU for under 2 hours–making my test results easy to reproduce
for readers. A transformer model diagram is provided with more detail than any
diagram readily obtainable on the web, and attention graphs are employed to show
the final results of self-attention on different sentences.