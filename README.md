StreamMyRelevance! (SMR)
========================

## Abstract

The prime aspect of quality for search-driven web applications is to provide users with the best possible results for a given query. Thus, it is necessary to predict the relevance of results a priori. Current solutions mostly engage clicks on results for respective predictions, but research has shown that it is highly beneficial to also consider additional features of user interaction. Nowadays, such interactions are produced in steadily growing amounts by internet users. Processing these requires streaming-based approaches and incrementally updateable relevance models. We present *StreamMyRelevance!*--a novel streaming-based system for ensuring quality of ranking in search engines. Our approach provides a complete pipeline from collecting interactions in real-time to processing them incrementally on the server side. We conducted a large-scale evaluation with real-world data from the hotel search domain. Results show that our system yields predictions as good as those of competing state-of-the-art systems, but by design of the underlying framework at higher efficiency, robustness and scalability.

## Publication(s)

- Maximilian Speicher, Sebastian Nuck, Andreas Both, and Martin Gaedke (2014). "StreamMyRelevance! Prediction of Result Relevance from Real-Time Interactions and its Application to Hotel Search". In: *Proc. ICWE*. http://link.springer.com/chapter/10.1007/978-3-319-08245-5_16

## Resources

This repository contains:

- in the folder **data** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The relevance models and corresponding training data for each of the ten datasets; produced using SMR.
  - The relevance models and corresponding training data for each of the ten datasets; produced using [TMR](https://github.com/maxspeicher/tellmyrelevance-resources).
