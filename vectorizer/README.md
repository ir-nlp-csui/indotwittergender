# Vectorizer
This research <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a> is using pre-trained vectorization models created from our own dataset to vectorize text features, such as:
- Bio
  - [BoW](bio_feat_bow_vec.pickle)
  - [BoW without stopwords](bio_feat_bow_stop_vec.pickle)
- Name (if the name is Hadi Syah Putra, then first name is Hadi, middle name is Syah, and last name is Putra)
  - [BoW](name_feat_ia_vec.pickle)
  - [BoW without last name](name_feat_ib_vec.pickle)
  - [BoW of first name](name_feat_ic_first_vec.pickle)
  - [BoW of middle name](name_feat_ic_middle_vec.pickle)
  - [BoW of last name](name_feat_ic_last_vec.pickle)
- Tweet (compressed in .zip format, so you need to unzip first)
  - [BoW](tweet_feat_bow_vec.zip)
  - [BoW without stopwords](tweet_feat_bow_stop_vec.zip)

The example script of how to leverage the vectorizers can be accessed [here](../jupyter-notebook/Feature%20Extraction.ipynb).

---
Riset <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a> menggunakan beberapa model vektorisasi yang telah dilatih dengan *dataset* yang kami miliki untuk melakukan vektorisasi fitur-fitur teks, seperti:
- Bio
  - [BoW](bio_feat_bow_vec.pickle)
  - [BoW tanpa *stopwords*](bio_feat_bow_stop_vec.pickle)
- Name (jika nama Hadi Syah Putra, maka nama awal Hadi, nama tengah Syah, dan nama akhir Putra)
  - [BoW](name_feat_ia_vec.pickle)
  - [BoW tanpa nama akhir](name_feat_ib_vec.pickle)
  - [BoW nama awal](name_feat_ic_first_vec.pickle)
  - [BoW nama tengah](name_feat_ic_middle_vec.pickle)
  - [BoW nama akhir](name_feat_ic_last_vec.pickle)
- Tweet (dikompresi dalam format .zip, jadi perlu diekstrak dulu)
  - [BoW](tweet_feat_bow_vec.zip)
  - [BoW tanpa *stopwords*](tweet_feat_bow_stop_vec.zip)

Contoh *script* cara memanfaatkan model-model vektorisasi dapat diakses di [sini](../jupyter-notebook/Feature%20Extraction.ipynb).
