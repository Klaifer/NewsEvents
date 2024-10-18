# Portuguese Natural Disasters Datasets

These are the datasets used to build the knowledge base on natural disasters in Brazil.
These are versions that have been simplified by removing the textual content of the news, since they are copyrighted.

| File Name                                               | Descriptions                                                                                        |
|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| [disasternews_train.csv](data/disasternews_train.csv)   | Urls for news, with label indicating relationship to disasters. Training data                       |
| [disasternews_test.csv](data/disasternews_test.csv)     | Urls for news, with label indicating relationship to disasters. Test data                           |
| [corpora.csv](data/corpora.csv)                         | Url's to disaster related news, automatically filtered                                              |
| [disastercat.csv](data/disastercat.csv)                 | News with label indicating disaster category (hydrometeorological, drought, geological, biological) |
| [disastergeo.json](data/disastergeo.json)               | Urls and entities. Entities are locations or dates and contain metadata.                            |
| [disasterevent_train.csv](data/disasterevent_train.csv) | Urls for news and event indication automatically generated. Training set.                           |
| [disasterevent_test.csv](data/disasterevent_test.csv)   | Urls for news and event indication automatically generated. Evaluation set.                         |

