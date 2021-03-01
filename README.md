# Covid19-Lies

To facilitate research in automatic COVID19 misinformation detection, we introduce the
<b>COVID-Lies</b> dataset for misconception detectionon Twitter. We have collected a dataset of 62 common misconceptions about the disease along with 6591 related tweets, identified and annotated by researchers from the UCI School of Medicine. Given a tweet, our data identifies whether any of the
known misconceptions are expressed by the tweet, and if so, whether the tweet propagates the misconception (<i>agree/pos</i>), is informative by contradicting it (<i>disagree/neg</i>), or is neither misinformative nor informative (<i>no stance/na</i>). 

For a full description of the data (Release v0.1), and associated models, please see our paper at the EMNLP 2020 Workshop on NLP for COVID-19 (Best Paper Award):

- **COVIDLies: Detecting COVID-19 Misinformation on Social Media** <br/>
  _Tamanna Hossain, Robert L. Logan IV, Arjuna Ugarte, Yoshitomo Matsubara, Sean Young, Sameer Singh_ <br/>
  ([PDF](https://openreview.net/pdf?id=FCna-s-ZaIE), [Discussion Forum](https://openreview.net/forum?id=FCna-s-ZaIE))

The repository contains the <b>COVID-Lies</b> annotated dataset. To comply with Twitter’s <a href = 'https://developer.twitter.com/en/developer-terms/agreement-and-policy'>Terms of Service </a>, we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use.

**Note:** This is an evolving dataset as annotation is ongoing and we plan to continually update known misconceptions. We invite researchers to build COVID19 misinformation detection systems and evaluate their performance using the presented dataset.

