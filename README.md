## word2vec_kmeans_LR
word2vec, kmeans, logistic regression
1. gensim word2vec model training , preservation , reloading and converting.
2. words clustering with kmeans.
3. logistic regression model training, preservation, reloading for sentence classification based on word vector.

**Dependent package:**
[gensim](https://radimrehurek.com/gensim/)
[scikit-learn](http://scikit-learn.org/stable/)
[jieba](https://github.com/fxsjy/jieba)
## some word vector results
```python
show_word_most_similar("演员", model, 10)
```

    1    群众演员      0.6856100559234619
    2    演員        0.6725834012031555
    3    跟组        0.6159209609031677
    4    替身        0.5973879098892212
    5    群众        0.5957409739494324
    6    男女老少      0.5860865712165833
    7    灯光师       0.5850135087966919
    8    摄影摄像      0.5805505514144897
    9    配音员       0.5796741843223572
    10   艺助        0.5716033577919006

