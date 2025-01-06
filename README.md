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

1000备用金借款平台:
1    融享钱包贷款平台            0.9621140956878662
2    金呗呗贷款               0.9596989154815674
3    金多宝app借款可靠吗         0.9561324119567871
4    千元借款快速放款平台          0.9515708684921265
5    犀益借款平台              0.9509480595588684
6    开心优品借款平台            0.9496006369590759
7    30天借款平台             0.9490481615066528
8    新资信借款平台             0.9474144577980042
9    赤兔宝借款靠谱吗            0.9446108341217041
10   小赢卡贷在线安装            0.9442781805992126
11   时光金科贷款app           0.9432960152626038
12   普享贷下载               0.943191647529602
13   融e借app下载官网          0.9412316083908081
14   荟融贷款                0.9408766627311707
15   国家贷款app             0.9390482306480408
16   2024能借钱的软件          0.9356690049171448
17   柚借贷款是真的吗            0.9346135258674622
18   丰融借钱app下载官网安卓       0.9336341023445129
19   微消费借钱               0.9331457614898682
20   美哩贷款是正规平台吗          0.9330275058746338



```python
show_word_most_similar("c++", model, 10)
```

    **1000备用金借款平台:**
    1    融享钱包贷款平台            0.9621140956878662
    2    金呗呗贷款               0.9596989154815674
    3    金多宝app借款可靠吗         0.9561324119567871
    4    千元借款快速放款平台          0.9515708684921265
    5    犀益借款平台              0.9509480595588684
    6    开心优品借款平台            0.9496006369590759
    7    30天借款平台             0.9490481615066528
    8    新资信借款平台             0.9474144577980042
    9    赤兔宝借款靠谱吗            0.9446108341217041
    10   小赢卡贷在线安装            0.9442781805992126
    11   时光金科贷款app           0.9432960152626038
    12   普享贷下载               0.943191647529602
    13   融e借app下载官网          0.9412316083908081
    14   荟融贷款                0.9408766627311707
    15   国家贷款app             0.9390482306480408
    16   2024能借钱的软件          0.9356690049171448
    17   柚借贷款是真的吗            0.9346135258674622
    18   丰融借钱app下载官网安卓       0.9336341023445129
    19   微消费借钱               0.9331457614898682
    20   美哩贷款是正规平台吗          0.9330275058746338
    
    **黑神话悟空类似什么游戏:**
    1    黑神话悟空是网游还是单机游戏      0.9780025482177734
    2    黑神话悟空是单机为什么开服       0.9696593880653381
    3    黑神话悟空有手游吗?          0.9680467844009399
    4    黑神话悟空共有几个周目         0.9669247269630432
    5    黑神话悟空是单机还是网游?       0.964763879776001
    6    黑神话悟空应该怎么玩          0.9645713567733765
    7    黑神话悟空怎么退            0.9611487984657288
    8    黑神话悟空好玩么            0.9590349793434143
    9    黑神话有手游版吗            0.9572020769119263
    10   黑神话悟空登陆ps4吗         0.9554254412651062
    11   黑神话悟空是腾讯的吗          0.9548118114471436
    12   黑神话悟空策划了多久          0.9547104239463806
    13   黑神话悟空研发了几年          0.9511393904685974
    14   黑神话:悟空在哪下载          0.9510976076126099
    15   黑神话悟空要什么配置才能玩       0.9510002732276917
    16   黑神话悟空多少个boss        0.949174165725708
    17   黑神话悟空什么时候上线-游戏懂哥的动态 0.9488646388053894
    18   黑神话悟空下载攻            0.9480547308921814
    19   黑神话悟空怎么玩?           0.9456764459609985
    20   黑神话悟空为什么那么多主播玩      0.9427462220191956



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

