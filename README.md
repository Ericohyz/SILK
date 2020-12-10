# SILK
## Walking with Attention: Self-guided Walking for Heterogeneous Graph Embedding
Here we provide an implementation of SILK.
### Environment settings

- python==3.8.2
- networkx==1.11
- numpy==1.11.2
- gensim==0.13.3
### How to run example:

```python
python main.py --input data/imdb --dimensions 128 --walk_length 50 --num_walks 10 --window-size 5 --alpha 0.5 --output movie_embeddings.txt
```
