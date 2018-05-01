ViVo: Video-Augmented Dictionary for Vocabulary Learning
========================================================

Yeshuang Zhu, Yuntao Wang, Chun Yu, Shaoyun Shi, Yankai Zhang, Shuang He, Peijun Zhao, Xiaojuan Ma, Yuanchun Shi
----------------------------------------------------------------------------------------------------------------

### Main contribution:
* designed, built, and evaluated a system that could facilitated vocabulary building by augmenting video resources.
* empirically studied the coverage of TOEFL (98%) and GRE (94%) in a corpus of TV episodes (a large portion) and movies (a small portion, about 5%)
* proposed an algorithm to map the sense-based video scene to the word entry that has the largest cosine similarity. (WSD: word sense disambiguation)
  - completely text-based
  - leverage word embeddings (trained on another corpus)
  - the video scene is represented by a vector, which is constructed by averaging vectors of the words from the context of the keyword weighted by TF-IDF.
* Evaluated the learning performance by testing how many words can be memorized right after watching the video/after two days. (According to the learning curve, the performance right after two days is similar to the long-term performance)
* Identified several characteristics of scenes that include the words most impressive to users
  - repeated
  - self-explanatory
  - humorous
  - emotive

### Research opportunities
* How to extend from memorizing the word to using the word? Can we help language learners form spontaneous conversations by properly orchestrating the video resources?
  - For example, in the discussion of the "repeated" factor that made some words appeared in that video easy to remember, one example was that P6 expressed that he would “never forget the word sergeant for the rest of life as it is repeated in too many scenes in Forrest Gump”. However, when will this kind of learning be helpful?
* Can we teach language learners interaction techniques rather than specific words? It's more related to certain contexts and the culture aspects of language learning.
* Will it be a good idea to force people to **use** a word in one's life?
