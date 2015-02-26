StreamMyRelevance! (SMR)
========================

## Abstract

The prime aspect of quality for search-driven web applications is to provide users with the best possible results for a given query. Thus, it is necessary to predict the relevance of results a priori. Current solutions mostly engage clicks on results for respective predictions, but research has shown that it is highly beneficial to also consider additional features of user interaction. Nowadays, such interactions are produced in steadily growing amounts by internet users. Processing these requires streaming-based approaches and incrementally updateable relevance models. We present *StreamMyRelevance! (SMR)*--a novel streaming-based system for ensuring quality of ranking in search engines. Our approach provides a complete pipeline from collecting interactions in real-time to processing them incrementally on the server side. We conducted a large-scale evaluation with real-world data from the hotel search domain. Results show that our system yields predictions as good as those of competing state-of-the-art systems:

- Bayesian Browsing Model (BBM),
- TellMyRelevance! (TMR),
- a click-only version of SMR, and
- a click-only version of TMR,

but by design of the underlying framework at higher efficiency, robustness and scalability.

## Publication(s)

- Maximilian Speicher, Sebastian Nuck, Andreas Both, and Martin Gaedke (2014). "StreamMyRelevance! Prediction of Result Relevance from Real-Time Interactions and its Application to Hotel Search". In: *Proc. ICWE*. http://link.springer.com/chapter/10.1007/978-3-319-08245-5_16
- Maximilian Speicher, Sebastian Nuck, Lars Wesemann, Andreas Both, and Martin Gaedke (2015). "From TMR to Turtle: Predicting Result Relevance from Mouse Cursor Interactions in Web Search". In: *Journal of Web Engineering*.

## Resources

This repository contains:

- in the folder **datasets** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The test/training data for each of the ten datasets; produced using SMR.
  - The test/training data for each of the ten datasets; produced using [TMR](https://github.com/maxspeicher/tellmyrelevance-resources).
- in the folder **models** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The relevance models for each of the ten datasets; produced using SMR.
  - The relevance models for each of the ten datasets; produced using [TMR](https://github.com/maxspeicher/tellmyrelevance-resources).
- in the folder **precision-recall-data**:
  - All data necessary to reproduce Precision-Recall and ROC analyses for all datasets and compared approaches (SMR, TMR, BBM, click-only SMR, click-only TMR).

## References

1. Liu, Chao, Fan Guo, and Christos Faloutsos. "BBM: bayesian browsing model from petabyte-scale data." In *Proceedings of the 15th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD '09)*. ACM, 2009.
2. Speicher, Maximilian, Andreas Both, and Martin Gaedke. "TellMyRelevance! Predicting the relevance of web search results from cursor interactions." In *Proceedings of the 22nd ACM International Conference on Information & Knowledge Management (CIKM '13)*. ACM, 2013.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
