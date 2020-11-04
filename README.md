# Implementing a State-of-the-art NLP Style Transfer Paper from Scratch - [Delete Retrieve Generate](https://arxiv.org/abs/1804.06437)
Implemented the state-of-the-art style transfer [Delete Retrieve Generate](https://arxiv.org/abs/1804.06437) paper from scratch.

Implemented all 4 models in the paper: DeleteOnly, DeleteAndRetrieve, TemplateBased, RetrieveOnly.
Goal of this is to build everything from scratch (including e.g. ngram generation, beam search algorithms, etc...) with minimal help from the internet.

Learned (intuitively understood from first principles, not just memorize & paste some code):
- efficient ngrams generation
- Became efficient @ using python Counter objs
- TF-IDF (in this case TF-IDF word overlap distance function)
- style embeddings
- concatening latent space with embeddings
- Beam search (this took SOO LONG since i had to implement from scratch, was def worth the struggle, feel like my brain physically grew after)
- BLEU scoring
