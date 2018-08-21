awesome-twitter-data
####################

A list of Twitter datasets and related resources. If you have a resource to add to the list, feel free to open a pull request, or email me at `shay.palachy@gmail.com <shay.palachy@gmail.com>`_.

The license, when known, is given in {curly brackets}. Dataset size is given in [square brackets] when available.


.. contents:: Table of Contents

.. section-numbering::


Twitter Datasets
================


Tweet datasets
--------------

* `Twitter Event Detection Dataset <http://mir.dcs.gla.ac.uk/resources/>`_  {?} [120m] - A collection of 120 million tweets, with relevance judgements for over 500 events.

* `Chirps <https://github.com/vered1986/Chirps/>`_ {`Apache License 2.0`_} [9m] - News-related tweets. Updated daily. Used in the paper `"Acquiring Predicate Paraphrases from News Tweets" <http://aclweb.org/anthology/S/S17/S17-1019.pdf>`_ by Vered Shwartz, Gabriel Stanovsky and Ido Dagan.

* `3 million Russian troll tweets <https://github.com/fivethirtyeight/russian-troll-tweets/>`_ {?} [3m] - Released by 538.

* `MovieTweetings <https://github.com/sidooms/MovieTweetings>`_ {`MIT`_} [725k] - A live movie rating dataset collected from Twitter.

* `350k MeToo tweets <https://data.world/rdeeds/350k-metoo-tweets>`_ {?} [350k]

* `Elon Musk Tweets-Until 4/6/17 <https://data.world/adamhelsinger/elon-musk-tweets-until-4-6-17>`_

* `2015 New Year's Resolutions <https://data.world/crowdflower/2015-new-years-resolutions>`_

* `Trump Tweets, 5/4/09 - 12/5/16 <https://data.world/lovesdata/trump-tweets-5-4-09-12-5-16>`_


Tweets datasets (labelled)
--------------------------

* `Weather-sentiment <https://data.world/crowdflower/weather-sentiment>`_


User datasets
-------------

* `Max Plank Institute's Twitter Dataset <http://twitter.mpi-sws.org/>`_ {?} [55m] - **The social graph component only of the following dataset:** 54,981,152 user accounts; 1,963,263,821 social (follow) links. 1,755,925,520 tweets.

* `Twitter Social Graph <http://an.kaist.ac.kr/traces/WWW2010.html>`_ {?} [41m] - From the `"What is Twitter, a Social Network or a News Media?" paper <http://an.kaist.ac.kr/traces/WWW2010.html>`_.

* `Twitter User Sample (Tweets Loud and Quiet) <https://github.com/jonbruner/twitter-analysis>`_ {`MPL 2.0`_} [400k] - Metadata of ~400,000 Twitter accounts, scraped between September 17, 2013, and October 19, 2013, as part of the work on the `"Tweets loud and quiet" article <https://www.oreilly.com/ideas/tweets-loud-and-quiet>`_. 

`Higgs Twitter Dataset <http://snap.stanford.edu/data/higgs-twitter.html>`_ {?} [456k] - The Higgs dataset has been built after monitoring the spreading processes on Twitter before, during and after the announcement of the discovery of a new particle with the features of the elusive Higgs boson on 4th July 2012.

* `ego-twitter <http://snap.stanford.edu/data/ego-Twitter.html>`_ [80k] - 80K nodes and 1.7 million edges.


Lost Datasets
-------------

* Kwak10www - A dataset consisting of 41.7 million user profiles, 1.47 billion social relations, 4,262 trending topics, and 106 million tweets. From the `"What is Twitter, a Social Network or a News Media?" paper <http://an.kaist.ac.kr/traces/WWW2010.html>`_. The social graph part of that data set is available on `the paper's webpage <http://an.kaist.ac.kr/traces/WWW2010.html>`_.

* `twitter7 <http://snap.stanford.edu/data/twitter7.html>`_ - A dataset consisting of nearly 580 million Twitter posts from 20 million users covering a 8 month period from June 2009 to February 2010. Estimated to be about 20-30% of all posts published on Twitter during that time frame. Created as part of [`J. Yang, J. Leskovec. Temporal Variation in Online Media. ACM International Conference on Web Search and Data Mining (WSDM '11), 2011. <http://ilpubs.stanford.edu:8090/984/1/paper-memeshapes.pdf>`_].

* burger2011 - A corpus consisting of 213 million tweets from 18.5 million users, in many different languages. Collected as part of `[John D. Burger, John C. Henderson, George Kim, and Guido Zarrella. 2011. Discriminating gender on Twitter. In Proceedings of the Conference on Empirical Methods in Natural Language Processing, pages 1301–1309] <http://www.aclweb.org/anthology/D11-1120>`_.



Other Lists
===========

* `Tweet ID Datasets <https://www.docnow.io/catalog/>`_ {`CC-BY 4.0`_} - A catalog of Twitter ID (i.e. contentless) datasets that are publicly available on the web.

* `Free Twitter Datasets by followthehashtag <http://followthehashtag.com/datasets/>`_

* `Twitter open datasets <https://opendata.stackexchange.com/questions/1545/twitter-open-datasets>`_ - A question on `opendata.stackexchange <https://opendata.stackexchange.com/>`_.


Data Collection Tools
=====================

* `twitter-dataset-collector <https://github.com/socialsensor/twitter-dataset-collector>`_ {`Apache License 2.0`_} [Java] - Facilitates the distribution of Twitter datasets by downloading sets of tweets (if still available) using their ids as input.

* `Expand The Edinburgh Twitter FSD Corpus <https://gist.github.com/emaadmanzoor/5019020>`_

* `Twitter-ratings <https://github.com/sidooms/Twitter-ratings>`_ {`MIT`_} - A collection of Python scripts to download and extract rating datasets from Twitter for multiple websites.


Analysis Tools
==============

* `OSU Twitter NLP Tools <https://github.com/aritter/twitter_nlp>`_ - A suite of Twitter NLP tools.

* `sentimentstwitter <https://github.com/alabid/sentimentstwitter>`_ {`MIT`_} - Given a tweet (that contains some text), estimate the sentiment (negative or positive) of the tweeter.

* `Twitter-L-LDA <https://github.com/harryaskham/Twitter-L-LDA>`_ {`GPLv3`_} - A set of tools for performing Labeled Latent Dirichlet Allocation on textual datasets, with an emphasis on Twitter profiles. Contains tools for analysing the results of model training and inference.

* `TwitterGenderPredictor <https://github.com/jtwool/TwitterGenderPredictor>`_

* `Tools by Alan Ritter <http://aritter.github.io/software.html>`_ - Several Twitter-related tools by Alan Ritter.


.. License Links

.. _Public Domain: https://en.wikipedia.org/wiki/Public_domain
.. _CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/
.. _AGPL-3.0: https://opensource.org/licenses/AGPL-3.0
.. _GPLv3: http://www.gnu.org/copyleft/gpl.html
.. _CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
.. _CC BY-NC 4.0: https://creativecommons.org/licenses/by-nc/4.0/
.. _Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
.. _MIT: https://en.wikipedia.org/wiki/MIT_License
.. _CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
.. _MPL 2.0: https://github.com/jonbruner/twitter-analysis
