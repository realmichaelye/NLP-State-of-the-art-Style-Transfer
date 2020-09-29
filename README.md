# Implementing a State-of-the-art NLP Style Transfer Paper from Scratch - [Delete Retrieve Generate](https://arxiv.org/abs/1804.06437)
Implemented the [Delete Retrieve Generate](https://arxiv.org/abs/1804.06437) paper from scratch without looking at its code, all in less than 7 days.

Implemented all 4 models in the paper: DeleteOnly, DeleteAndRetrieve, TemplateBased, RetrieveOnly
Note: I Credited every stackoverflow question I did search up, everything else was from scratch.

Learned (intuitively understood, not just memorize & paste some code):
- the basics: panda dataframe manipulation, pytorch sequence2sequence neural networks
- efficient ngrams generation
- Became efficient @ using python Counter objs
- TF-IDF (in this case TF-IDF word overlap distance function)
- style embeddings
- concatening latent space with embeddings
- Beam search (this took SOO LONG since i had to implement from scratch, was def worth the struggle, feel like my brain physically grew after)
- BLEU scoring
