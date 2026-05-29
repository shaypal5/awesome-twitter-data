awesome-twitter-data
####################
|Awesome| |CC0|

.. |Awesome| image:: https://awesome.re/badge.svg
   :target: https://awesome.re

A list of Twitter datasets and related resources, released under `CC0 <https://creativecommons.org/publicdomain/zero/1.0/>`_. If you have a resource to add to the list, feel free to open a pull request, or email me at `shay.palachy@gmail.com <shay.palachy@gmail.com>`_.

The license, when known, is given in {curly brackets}. Dataset size is given in [square brackets] when available.

Entry format and availability
=============================

Dataset entries should use this format when possible:

``Name`` {license} [size] - Availability; short neutral description.

Availability values used in this list:

* Full text - tweet text or full tweet JSON is available.
* Tweet IDs - tweet IDs are available and must be hydrated separately.
* Labelled data - annotations or task labels are available.
* Metadata - profile, rating, annotation, or derived metadata is available.
* Benchmark - benchmark tasks, splits, or evaluation labels are available.
* Graph - user, follow, mention, retweet, list, or other network data is available.
* By request - the dataset is described publicly but access requires contacting the authors.
* Partially available - only a documented subset of the original dataset is available.
* Lost - the dataset is no longer available from a known working source.

Values can be combined when a resource provides multiple data types or access modes.

Prefer primary dataset pages in the dataset sections. Mirrors, warehouses, and broad search pages belong in `Other Lists`_ unless they provide a clearly distinct release.


.. contents:: Table of Contents

.. section-numbering::


Twitter Datasets
================


Tweet text and full-content datasets
------------------------------------

* `3 million Russian troll tweets <https://github.com/fivethirtyeight/russian-troll-tweets/>`_ {?} [3m] - Full text; released by 538.

* `ArchiveTeam JSON Download of Twitter Stream, 2011 - 2022 [16bn] <https://archive.org/search.php?query=twitterstream&sort=-publicdate>`_ - Full text; archived Twitter stream JSON dumps.

* `Cheng-Caverlee-Lee <https://archive.org/details/twitter_cikm_2010>`_ {?} [5m] - Full text; scraped public Twitter updates used in a geolocation academic project.

* `Chirps <https://github.com/vered1986/Chirps/>`_ {`Apache License 2.0`_} [9m] - Full text; news-related tweets, updated daily. Used in the paper `"Acquiring Predicate Paraphrases from News Tweets" <http://aclweb.org/anthology/S/S17/S17-1019.pdf>`_ by Vered Shwartz, Gabriel Stanovsky and Ido Dagan.

* `Elon Musk Tweets-Until 4/6/17 <https://data.world/adamhelsinger/elon-musk-tweets-until-4-6-17>`_ - Full text; Elon Musk tweets through April 6, 2017.

* `Lerman Twitter 2010 Dataset <http://academictorrents.com/details/d8b3a315172c8d804528762f37fa67db14577cdb>`_ [2.8m] - Full text; Graph; tweets containing URLs posted during October 2010, plus follower links for active users.

* `Trump Tweets, 5/4/09 - 12/5/16 <https://data.world/lovesdata/trump-tweets-5-4-09-12-5-16>`_ - Full text; Donald Trump tweets from May 4, 2009 to December 5, 2016.

* `Twitter_2010 <https://www.isi.edu/~lerman/downloads/twitter/twitter2010.html>`_ {?} [2m] - Full text; released by Kristina Lerman at USC.


Tweet ID datasets
-----------------

* `72 Hours of #Gamersgate <https://medium.com/message/72-hours-of-gamergate-e00513f7cf5d>`_ [313K] - Tweet IDs; tweets from a 72-hour #Gamergate collection.

* `Arab Spring Twitter Dataset <http://dfreelon.org/2012/02/11/arab-spring-twitter-data-now-available-sort-of/>`_ {?} [8m] - Tweet IDs; Arab Spring tweets separated by country, without tweet contents.

* `COVID-19 Twitter Dataset <https://github.com/thepanacealab/covid19_twitter>`_ {`CC0`_} [100m] - Tweet IDs; COVID-19 chatter from the Twitter Stream. Can also be found `on Zenodo.org <https://zenodo.org/record/3735274>`_.

* `COVID-19-TweetIDs <https://github.com/echen102/COVID-19-TweetIDs>`_ {`CC BY-NC-SA 4.0`_} [1bn+] - Tweet IDs; COVID-19 related research collection.

* `CoVaxxy <https://github.com/osome-iu/CoVaxxy>`_ {`CC-BY 4.0`_} [198m] - Tweet IDs; COVID-19 vaccine discourse.

* `CrisisLexT26 <https://crisislex.org/data-collections.html#CrisisLexT26>`_ [28k] - Tweet IDs; Labelled data; crisis-related tweets for 26 crisis events.

* `CrisisNLP <https://crisisnlp.qcri.org/>`_ [?] - Tweet IDs; crisis-related datasets for NLP and humanitarian response research.

* `GeoCoV19 <https://zenodo.org/records/3878599>`_ {`CC-BY 4.0`_} [500m+] - Tweet IDs; geolocated COVID-19 tweets.

* `Geotagged COVID-19 Twitter Dataset <http://covid19research.site/geo-tagged_twitter_datasets/>`_ {?} [650k] - Tweet IDs; geotagged COVID-19 tweets from the United States.

* `ODPtweets <https://www.zubiaga.org/datasets/odptweets/>`_ {?} [25m] - Tweet IDs; ODP-categorized tweet IDs and usernames, without redistributed tweet text.

* `RepLab 2013 Dataset <http://nlp.uned.es/replab2013/>`_ - Tweet IDs; English and Spanish Twitter data with more than 142,000 tweets.

* `TweetsKB <https://data.gesis.org/tweetskb/>`_ {?} [1.5bn] - Tweet IDs; Metadata; large knowledge base with extracted metadata and named entities.


Labelled and benchmark datasets
-------------------------------

* `2015 New Year's Resolutions <https://data.world/crowdflower/2015-new-years-resolutions>`_ - Labelled data; tweets about New Year's resolutions.

* `Crowdflower Gender Classifier Data <https://data.world/crowdflower/gender-classifier-data>`_ [20k] - Labelled data; Twitter profile gender classifier dataset with username, tweet, profile metadata, image, location, and profile colors.

* `First GOP Debate Twitter Sentiment <https://data.world/crowdflower/first-gop-debate-twitter-sentiment>`_ {?} [13k] - Labelled data; tweets about the 2016 Republican debate annotated for sentiment.

* `Geoparse Benchmark Open Dataset <https://revealproject.eu/geoparse-benchmark-open-dataset/>`_ {`BSD-4_Clause`_} [?] - Labelled data; disaster tweets manually labelled with location entries at building, street, and region levels.

* `Hate Speech and Offensive Language <https://github.com/t-davidson/hate-speech-and-offensive-language>`_ {`MIT`_} [24k] - Labelled data; tweets labelled as hate speech, offensive language, or neither.

* `Natural Language Processing with Disaster Tweets <https://www.kaggle.com/competitions/nlp-getting-started>`_ {?} [10k] - Labelled data; tweets labelled as disaster-related or not disaster-related.

* `PHEME rumour scheme dataset <https://figshare.com/articles/dataset/PHEME_rumour_scheme_dataset_journalism_use_case/2068650>`_ {`CC-BY 4.0`_} [?] - Labelled data; Twitter conversation threads annotated for rumour and stance analysis.

* `PHEME veracity dataset <https://figshare.com/articles/dataset/PHEME_dataset_for_Rumour_Detection_and_Veracity_Classification/6392078>`_ {`CC-BY 4.0`_} [?] - Labelled data; Twitter rumour conversations annotated for rumour detection and veracity classification.

* `Sanders Analytics <http://www.sananalytics.com/lab/twitter-sentiment/>`_ {?} [5k] - Labelled data; hand-classified tweets across four topics. Use Internet Archive's `Wayback Machine <https://archive.org/web/>`_ to get the data.

* `Sanders Analytics Sentiment-labelled tweets <https://github.com/zfz/twitter_corpus>`_ {?} [5513] - Labelled data; sentiment-labelled tweets.

* `SemEval-2016 Task 6 stance dataset <http://alt.qcri.org/semeval2016/task6/>`_ {?} [?] - Labelled data; tweets annotated for stance detection.

* `SemEval-2017 Task 4 Twitter sentiment datasets <https://alt.qcri.org/semeval2017/task4/>`_ {?} [?] - Labelled data; Twitter sentiment classification datasets used in the SemEval-2017 shared task.

* `SenWave <https://github.com/gitdevqiang/SenWave>`_ {`Apache License 2.0`_} [10k] - Labelled data; tweets annotated with fine-grained COVID-19 sentiment and emotion labels.

* `Sentiment140 <http://help.sentiment140.com/for-students/>`_ - Labelled data; automatically labelled using positive and negative emoticons.

* `TweetEval <https://github.com/cardiffnlp/tweeteval>`_ {?} [?] - Benchmark; Labelled data; unified Twitter benchmark datasets for seven tweet classification tasks.

* `Twitter US Airline Sentiment <https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment>`_ {?} [14k] - Labelled data; airline-related tweets labelled for positive, neutral, and negative sentiment.

* `Weather-sentiment <https://data.world/crowdflower/weather-sentiment>`_ - Labelled data; weather-related tweets annotated for sentiment.


Metadata, ratings, and user datasets
------------------------------------

* `MovieTweetings <https://github.com/sidooms/MovieTweetings>`_ {`MIT`_} [725k] - Metadata; live movie rating dataset collected from Twitter.

* `Twitter User Sample (Tweets Loud and Quiet) <https://github.com/jonbruner/twitter-analysis>`_ {`MPL 2.0`_} [400k] - Metadata; Twitter account metadata scraped between September 17, 2013 and October 19, 2013 for the `"Tweets loud and quiet" article <https://www.oreilly.com/ideas/tweets-loud-and-quiet>`_.


Graph and network datasets
--------------------------

* `Arizona State University Twitter Data Set <http://socialcomputing.asu.edu/datasets/Twitter>`_ [11m] - Graph; Twitter network dataset. `Alternate download (via torrent) here <http://academictorrents.com/details/2399616d26eeb4ae9ac3d05c7fdd98958299efa9>`_.

* `ego-twitter <http://snap.stanford.edu/data/ego-Twitter.html>`_ [80k] - Graph; 80K nodes and 1.7 million edges.

* `Higgs Twitter Dataset <http://snap.stanford.edu/data/higgs-twitter.html>`_ {?} [456k] - Graph; Twitter activity and social network data around the July 2012 Higgs boson announcement.

* Kwak10www {?} [41.7m users] - Partially available; Graph; the social graph remains available from the `"What is Twitter, a Social Network or a News Media?" paper page <http://an.kaist.ac.kr/traces/WWW2010.html>`_, while the full tweet, profile, and trend dataset is otherwise unavailable.

* `Max Plank Institute's Twitter Dataset <http://twitter.mpi-sws.org/>`_ {?} [55m] - Graph; social graph component of a larger dataset with 54,981,152 user accounts and 1,963,263,821 social links.

* `Multiple Social Network Views Dataset <http://mlg.ucd.ie/aggregation/>`_ {?} [5 datasets] - Graph; topical Twitter user-network datasets with manually curated communities and multiple sparse-matrix views.

* `soTweet <http://www-sop.inria.fr/members/Arnaud.Legout/Projects/sotweet.html>`_ [full] {X} - By request; Graph; full Twitter social graph from 2012, plus anonymized social-click data from 2016.

* `The SNAP 2010 Dataset <https://snap.stanford.edu/data/twitter-2010.html>`_ [41m] - Graph; 41m nodes and 1.4 billion edges.

* `Twitter 15M <http://konect.cc/networks/twitter/>`_ {?} [15m] - Graph; Twitter follower network mirrored in the KONECT network collection.

* `Twitter Data - NIPS 2012 <http://academictorrents.com/details/046cf7a75db2a530b1505a4ce125fbe0031f4661>`_ [81k] - Graph; Twitter circles/lists dataset with node features, circles, and ego networks.

* `Twitter Social Graph <http://an.kaist.ac.kr/traces/WWW2010.html>`_ {?} [41m] - Graph; social graph from the `"What is Twitter, a Social Network or a News Media?" paper <http://an.kaist.ac.kr/traces/WWW2010.html>`_.

* `twitter-2010 at LAW <https://law.di.unimi.it/webdata/twitter-2010/>`_ {?} [41m] - Graph; WebGraph-format release of the 2010 Twitter follower graph.

Lost or unavailable datasets
-----------------------------

* burger2011 - Lost; 213 million tweets from 18.5 million users in many languages. Collected as part of `[John D. Burger, John C. Henderson, George Kim, and Guido Zarrella. 2011. Discriminating gender on Twitter. In Proceedings of the Conference on Empirical Methods in Natural Language Processing, pages 1301–1309] <http://www.aclweb.org/anthology/D11-1120>`_.

* calufa2011 - Lost; 200+ million tweets from 13+ million users, 173 GB uncompressed, mysql format (543 million rows). The archive.org copy has been taken down: https://archive.org/details/2011-05-calufa-twitter-sql. Several mentions on HackerNews: https://news.ycombinator.com/item?id=2633384

* fifa2014 - Lost; 86k tweets from 2014 FIFA World Cup. Described here: https://opendata.stackexchange.com/a/4015, previously available from a data-provider which is no longer online (topsy.com). One potential source is https://ankeshanand.carto.com/tables/fifatweets/public, although the data export is not clear.

* `Twitter Event Detection Dataset <http://mir.dcs.gla.ac.uk/resources/>`_  {?} [120m] - Lost; collection of 120 million tweets, with relevance judgements for over 500 events.

* `twitter7 <http://snap.stanford.edu/data/twitter7.html>`_ - Lost; nearly 580 million Twitter posts from 20 million users from June 2009 to February 2010. Created as part of [`J. Yang, J. Leskovec. Temporal Variation in Online Media. ACM International Conference on Web Search and Data Mining (WSDM '11), 2011. <http://ilpubs.stanford.edu:8090/984/1/paper-memeshapes.pdf>`_].

Other Lists
===========

* `Tweet ID Datasets <https://catalog.docnow.io/>`_ {`CC-BY 4.0`_} - A catalog of Twitter ID (i.e. contentless) datasets that are publicly available on the web.

* `Free Twitter Datasets by followthehashtag <http://followthehashtag.com/datasets/>`_

* `Netzschleuder Twitter networks <https://networks.skewed.de/?search=Twitter>`_ - A searchable catalog of graph datasets with Twitter-related network entries.

* `KONECT Twitter networks <http://konect.cc/networks/>`_ - Network dataset catalog with several Twitter graph datasets.

* `data.world Twitter datasets <https://data.world/datasets/twitter>`_ - A searchable catalog of Twitter-related datasets on data.world.

* `Kaggle Twitter datasets <https://www.kaggle.com/search?q=twitter+in%3Adatasets>`_ - A searchable catalog of Twitter-related datasets on Kaggle.

* `Twitter open datasets <https://opendata.stackexchange.com/questions/1545/twitter-open-datasets>`_ - A question on `opendata.stackexchange <https://opendata.stackexchange.com/>`_.

* `Datasets for PAN's shared tasks on digital text forensics <https://pan.webis.de/data.html>`_ - Not Tweeter, but close.


Tools
=====

Data Collection
---------------

* `twitter-dataset-collector <https://github.com/socialsensor/twitter-dataset-collector>`_ {`Apache License 2.0`_} [Java] - Facilitates the distribution of Twitter datasets by downloading sets of tweets (if still available) using their ids as input.

* `Expand The Edinburgh Twitter FSD Corpus <https://gist.github.com/emaadmanzoor/5019020>`_

* `Twitter-ratings <https://github.com/sidooms/Twitter-ratings>`_ {`MIT`_} - A collection of Python scripts to download and extract rating datasets from Twitter for multiple websites.

* `RepLab 2013 Twitter text downloaded <http://nlp.uned.es/replab2013/>`_ - Find it at the bottom of the page.

* `TwitterAPI.io <https://twitterapi.io>`_ - A real-time Twitter/X data API for collecting tweets, user profiles, followers, advanced search results and the live tweet stream via REST endpoints.

* `Xquik <https://github.com/Xquik-dev/x-twitter-scraper>`_ - X/Twitter data extraction platform - 20 bulk tools (followers, replies, quotes, retweets, likes, mentions, lists, communities), REST API, account monitoring, HMAC webhooks.

* `TweetClaw <https://github.com/Xquik-dev/tweetclaw>`_ {`MIT`_} [OpenClaw plugin] - Collect X/Twitter data through Xquik from OpenClaw: search tweets and replies, export followers, look up users, monitor tweets, receive webhooks, review media workflows, and run giveaway draws.


Analysis
--------

* `OSU Twitter NLP Tools <https://github.com/aritter/twitter_nlp>`_ - A suite of Twitter NLP tools.

* `sentimentstwitter <https://github.com/alabid/sentimentstwitter>`_ {`MIT`_} - Given a tweet (that contains some text), estimate the sentiment (negative or positive) of the tweeter.

* `Twitter-L-LDA <https://github.com/harryaskham/Twitter-L-LDA>`_ {`GPLv3`_} - A set of tools for performing Labeled Latent Dirichlet Allocation on textual datasets, with an emphasis on Twitter profiles. Contains tools for analysing the results of model training and inference.

* `TwitterGenderPredictor <https://github.com/jtwool/TwitterGenderPredictor>`_ by `jtwool <https://github.com/jtwool>`_ - Does what it says. Has a `simple package wrapper <https://github.com/shaypal5/speks>`_ by Shay Palachy.

* `Tools by Alan Ritter <http://aritter.github.io/software.html>`_ - Several Twitter-related tools by Alan Ritter.


Academic Papers
===============

* Learning Multiview Embeddings of Twitter Users

Demographics Prediction
-----------------------

* `Developing Age and Gender Predictive Lexica over Social Media, 2014 <http://wwbp.org/papers/emnlp2014_developingLexica.pdf>`_ - We derive predictive lexica (words and weights) for age and gender using regression and classification models from word usage in Facebook, blog, and Twitter data with associated demographiclabels. The lexica, made publicly available, achieved state-of-the-art accuracy in language based age and gender prediction over Facebook and Twitter, and were evaluated for generalization across social media genres as well as in limited message situations.

* Predicting the Demographics of Twitter Users from Website Traffic Data

* Inferring Perceived Demographics from User Emotional Tone and User-Environment Emotional Contrast

* Mining User Interests to Predict Perceived Psycho-Demographic Traits on Twitter

* Why Gender and Age Prediction from Tweets is Hard: Lessons from a Crowdsourcing Experiment

* Who tweets? deriving the demographic characteristics of age, occupation and social class from twitter user meta-data


Articles & blog posts
=====================

* `Twitter sentiment analysis using Python and NLTK <http://ww1.gbsheli.com/2009/03/twitgraph-en.html>`_

* `72 Hours of #Gamersgate <https://medium.com/message/72-hours-of-gamergate-e00513f7cf5d>`_

* `A beginner's guide to collecting Twitter data (and a bit of web scraping) <https://knightlab.northwestern.edu/2014/03/15/a-beginners-guide-to-collecting-twitter-data-and-a-bit-of-web-scraping/>`_


Contributing
============

- Please check for duplicates first.
- Keep descriptions short, simple and unbiased.
- Please make an individual commit for each suggestion
- Add a new category if needed.
- Prefer primary dataset pages. Add mirrors, warehouses, and broad search pages to `Other Lists`_ unless they provide a clearly distinct release.
- For datasets, please keep the format when possible: ``Name`` {license} [size] - Availability; short neutral description.
- For Twitter/X datasets, state whether the resource provides full tweet text, tweet IDs only, metadata, graph data, or access by request.
- Include license and availability details when the source states them. Use {?} only when the license is not clear.
- If a source is unavailable, add it to `Lost or unavailable datasets`_ instead of a live dataset section.

Thank you for your suggestions!


License
=======
|CC0|

.. |CC0| image:: https://licensebuttons.net/p/zero/1.0/88x31.png
   :target: https://creativecommons.org/publicdomain/zero/1.0/

To the extent possible under law, `Shay Palachy <http://shaypalachy.com>`_ has waived all copyright and related or neighboring rights to this work.

.. License Links

.. _Public Domain: https://en.wikipedia.org/wiki/Public_domain
.. _CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/
.. _AGPL-3.0: https://opensource.org/licenses/AGPL-3.0
.. _GPLv3: https://www.gnu.org/licenses/gpl-3.0.en.html
.. _CC0:  https://creativecommons.org/publicdomain/zero/1.0/
.. _CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
.. _CC BY-NC 4.0: https://creativecommons.org/licenses/by-nc/4.0/
.. _Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
.. _MIT: https://en.wikipedia.org/wiki/MIT_License
.. _CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
.. _MPL 2.0: https://github.com/jonbruner/twitter-analysis
.. _BSD-4_Clause: https://en.wikipedia.org/wiki/BSD_licenses#4-clause_license_(original_%22BSD_License%22)
