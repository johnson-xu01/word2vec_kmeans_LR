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
show_word_most_similar("java", model, 10)
```

    1    java开发    0.6753628253936768
    2    php       0.6690933704376221
    3    程序员       0.6263120174407959
    4    ios开发     0.6101993322372437
    5    php开发     0.5862185955047607
    6    安卓开发      0.5664030313491821
    7    java程序员   0.5655223727226257
    8    c++       0.5587760806083679
    9    自动化测试     0.5531591176986694
    10   c#        0.5460507869720459



```python
show_word_most_similar("c++", model, 10)
```

    1    c#        0.7780156135559082
    2    asp.net   0.7592251896858215
    3    python    0.7552355527877808
    4    后端        0.7228183746337891
    5    html      0.7221277356147766
    6    lua       0.7180061340332031
    7    delphi    0.7093928456306458
    8    u3d       0.7091572284698486
    9    qt        0.7084509134292603
    10   前段        0.7080010771751404



```python
show_word_most_similar("hr", model, 10)
```

    1    员工关系      0.5777395367622375
    2    人力资源部     0.5712631940841675
    3    人力资源      0.5214904546737671
    4    培训专员      0.5186867117881775
    5    人事部       0.5120692253112793
    6    招聘主管      0.5031419992446899
    7    招聘助理      0.49358999729156494
    8    人资        0.47089171409606934
    9    人力资源助理    0.4646800756454468
    10   hrbp      0.4390413463115692



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

