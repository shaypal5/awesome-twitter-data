awesome-twitter-data
####################
|Awesome| |CC0|

.. |Awesome| image:: https://awesome.re/badge.svg
   :target: https://awesome.re

A list of Twitter datasets and related resources, released under `CC0 <https://creativecommons.org/publicdomain/zero/1.0/>`_. If you have a resource to add to the list, feel free to open a pull request, or email me at `shay.palachy@gmail.com <shay.palachy@gmail.com>`_.

The license, when known, is given in {curly brackets}. Dataset size is given in [square brackets] when available.


.. contents:: Table of Contents

.. section-numbering::


Twitter Datasets
================


Tweet datasets
--------------

* `Chirps <https://github.com/vered1986/Chirps/>`_ {`Apache License 2.0`_} [9m] - News-related tweets. Updated daily. Used in the paper `"Acquiring Predicate Paraphrases from News Tweets" <http://aclweb.org/anthology/S/S17/S17-1019.pdf>`_ by Vered Shwartz, Gabriel Stanovsky and Ido Dagan.

* `COVID-19 Twitter Dataset <https://github.com/thepanacealab/covid19_twitter>`_ {`CC0`_} [100m] - Tweets acquired from the Twitter Stream related to COVID-19 chatter. Can also be found `on Zenodo.org <https://zenodo.org/record/3735274>`_.

* `Arab Spring Twitter Dataset <http://dfreelon.org/2012/02/11/arab-spring-twitter-data-now-available-sort-of/>`_ {?} [8m] - Roughly 8 million tweets related to the Arab Spring, separated by country. Contain tweet IDs and twitter IDS, but no tweet contents.

* `Cheng-Caverlee-Lee <https://archive.org/details/twitter_cikm_2010>`_ {?} [5m] - A collection of scraped public twitter updates used in coordination with an academic project to study the geolocation data related to twittering.

* `3 million Russian troll tweets <https://github.com/fivethirtyeight/russian-troll-tweets/>`_ {?} [3m] - Released by 538.

* `Lerman Twitter 2010 Dataset <http://academictorrents.com/details/d8b3a315172c8d804528762f37fa67db14577cdb>`_ [2.8m] - Contains tweets containing URLs that have been posted on Twitter during October 2010. In addition to tweets, links of tweeting users were followed, allowing the reconstruction the follower graph of active (tweeting) users. 


* `Twitter_2010 <https://www.isi.edu/~lerman/downloads/twitter/twitter2010.html>`_ {?} [2m] - Released by Kristina Lerman at USC.

* `MovieTweetings <https://github.com/sidooms/MovieTweetings>`_ {`MIT`_} [725k] - A live movie rating dataset collected from Twitter.

* `Sanders Analytics Sentiment-labelled tweets <https://github.com/zfz/twitter_corpus>`_ {?} [5513]

* `Elon Musk Tweets-Until 4/6/17 <https://data.world/adamhelsinger/elon-musk-tweets-until-4-6-17>`_

* `2015 New Year's Resolutions <https://data.world/crowdflower/2015-new-years-resolutions>`_

* `Trump Tweets, 5/4/09 - 12/5/16 <https://data.world/lovesdata/trump-tweets-5-4-09-12-5-16>`_

* `ArchiveTeam JSON Download of Twitter Stream, 2011 - ongoing <https://archive.org/search.php?query=twitterstream&sort=-publicdate>`_


Tweet ID datasets
~~~~~~~~~~~~~~~~~

* `72 Hours of #Gamersgate <https://medium.com/message/72-hours-of-gamergate-e00513f7cf5d>`_ [313K]

* `RepLab 2013 Dataset <http://nlp.uned.es/replab2013/>`_ - RepLab 2013 dataset uses Twitter data in English and Spanish (more than 142,000 tweets).


Tweet datasets (labelled)
--------------------------

* `Sentiment140 <http://help.sentiment140.com/for-students/>`_ - Automatically laballed; authors assume that any tweet with positive emoticons, like :), are positive, and tweets with negative emoticons, like :(, are negative. 

* `Weather-sentiment <https://data.world/crowdflower/weather-sentiment>`_

* `Crowdflower Gender Classifier Data <https://data.world/crowdflower/gender-classifier-data>`_ [20k] - Contributors were asked to simply view a Twitter profile and judge whether the user was a male, a female, or a brand (non-individual). The dataset contains 20,000 rows, each with a user name, a random tweet, account profile and image, location, and even link and sidebar color.

* `Sanders Analytics <http://www.sananalytics.com/lab/twitter-sentiment/>`_ {?} [5k]- Use Internet Archive's `Wayback Machine <https://archive.org/web/>`_ to get the data.  The dataset consists of 5513 hand-classified tweets. Each tweet was classified with respect to one of four different topics.

* `Geoparse Benchmark Open Dataset <https://revealproject.eu/geoparse-benchmark-open-dataset/>`_ {`BSD-4_Clause`_} [?] - The geoparsing benchmark dataset contains 1000’s of tweets recorded during 4 different natural disasters. These events are Hurricane Sandy 2012, Milan Blackouts 2013, Turkish Earthquake 2012 and the Christchurch Earthquake 2012. Each tweet in the dataset has been manually labelled with location entries at the building, street and region levels to provide a gold standard for evaluation work. The data consists of the full JSON serialized tweet metadata (i.e. including text) with an additional ‘entities’ field of type ‘mentions’ for the ground truth location annotations.


User datasets
-------------

* `Max Plank Institute's Twitter Dataset <http://twitter.mpi-sws.org/>`_ {?} [55m] - **The social graph component only of the following dataset:** 54,981,152 user accounts; 1,963,263,821 social (follow) links. 1,755,925,520 tweets.

* `Twitter Social Graph <http://an.kaist.ac.kr/traces/WWW2010.html>`_ {?} [41m] - From the `"What is Twitter, a Social Network or a News Media?" paper <http://an.kaist.ac.kr/traces/WWW2010.html>`_.

* `Arizona State University Twitter Data Set <http://socialcomputing.asu.edu/datasets/Twitter>`_ [11m] - `Alternate download (via torrent) here <http://academictorrents.com/details/2399616d26eeb4ae9ac3d05c7fdd98958299efa9>`_.

* `Twitter User Sample (Tweets Loud and Quiet) <https://github.com/jonbruner/twitter-analysis>`_ {`MPL 2.0`_} [400k] - Metadata of ~400,000 Twitter accounts, scraped between September 17, 2013, and October 19, 2013, as part of the work on the `"Tweets loud and quiet" article <https://www.oreilly.com/ideas/tweets-loud-and-quiet>`_. 

* `Higgs Twitter Dataset <http://snap.stanford.edu/data/higgs-twitter.html>`_ {?} [456k] - The Higgs dataset has been built after monitoring the spreading processes on Twitter before, during and after the announcement of the discovery of a new particle with the features of the elusive Higgs boson on 4th July 2012.

* `Twitter Data - NIPS 2012	<http://academictorrents.com/details/046cf7a75db2a530b1505a4ce125fbe0031f4661>`_ [81k] - This dataset consists of 'circles' (or 'lists') from Twitter. Twitter data was crawled from public sources. The dataset includes node features (profiles), circles, and ego networks.

* `ego-twitter <http://snap.stanford.edu/data/ego-Twitter.html>`_ [80k] - 80K nodes and 1.7 million edges.

* `soTweet <http://www-sop.inria.fr/members/Arnaud.Legout/Projects/sotweet.html>`_ [full] {X} - This projects includes a Twitter social graph dataset - of the full Twitter network - from 2012. Also includes an anonymized dataset of social clicks from 2016. Both are available on request.



Lost Datasets
-------------

* `Twitter Event Detection Dataset <http://mir.dcs.gla.ac.uk/resources/>`_  {?} [120m] - A collection of 120 million tweets, with relevance judgements for over 500 events.

* Kwak10www - A dataset consisting of 41.7 million user profiles, 1.47 billion social relations, 4,262 trending topics, and 106 million tweets, collected between July 6th, 2009 to July 31st, 2009. From the `"What is Twitter, a Social Network or a News Media?" paper <http://an.kaist.ac.kr/traces/WWW2010.html>`_. The social graph part of that data set is available on `the paper's webpage <http://an.kaist.ac.kr/traces/WWW2010.html>`_.

* `twitter7 <http://snap.stanford.edu/data/twitter7.html>`_ - A dataset consisting of nearly 580 million Twitter posts from 20 million users covering a 8 month period from June 2009 to February 2010. Estimated to be about 20-30% of all posts published on Twitter during that time frame. Created as part of [`J. Yang, J. Leskovec. Temporal Variation in Online Media. ACM International Conference on Web Search and Data Mining (WSDM '11), 2011. <http://ilpubs.stanford.edu:8090/984/1/paper-memeshapes.pdf>`_].

* burger2011 - A corpus consisting of 213 million tweets from 18.5 million users, in many different languages. Collected as part of `[John D. Burger, John C. Henderson, George Kim, and Guido Zarrella. 2011. Discriminating gender on Twitter. In Proceedings of the Conference on Empirical Methods in Natural Language Processing, pages 1301–1309] <http://www.aclweb.org/anthology/D11-1120>`_.

* calufa2011 - 200+ million tweets from 13+ million users, 173 GB uncompressed, mysql format (543 million rows). The archive.org copy has been taken down: https://archive.org/details/2011-05-calufa-twitter-sql. Several mentions on HackerNews: https://news.ycombinator.com/item?id=2633384

* fifa2014 - 86k tweets from 2014 FIFA World Cup. Described here: https://opendata.stackexchange.com/a/4015, previously available from a data-provider which is no longer online (topsy.com). One potential source is https://ankeshanand.carto.com/tables/fifatweets/public, although the data export is not clear. There are several blogs describing this data and its analysis, so contacting those authors may be a way to revive this dataset.

Other Lists
===========

* `Tweet ID Datasets <https://www.docnow.io/catalog/>`_ {`CC-BY 4.0`_} - A catalog of Twitter ID (i.e. contentless) datasets that are publicly available on the web.

* `Free Twitter Datasets by followthehashtag <http://followthehashtag.com/datasets/>`_

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
- For datasets, please keep the format when possible: The license, when known, is given in {curly brackets}. Dataset size is given in [square brackets] when available.

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
.. _GPLv3: http://www.gnu.org/copyleft/gpl.html
.. _CC0:  https://creativecommons.org/publicdomain/zero/1.0/
.. _CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
.. _CC BY-NC 4.0: https://creativecommons.org/licenses/by-nc/4.0/
.. _Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
.. _MIT: https://en.wikipedia.org/wiki/MIT_License
.. _CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
.. _MPL 2.0: https://github.com/jonbruner/twitter-analysis
.. _BSD-4_Clause: https://en.wikipedia.org/wiki/BSD_licenses#4-clause_license_(original_%22BSD_License%22)
