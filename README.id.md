# indotwittergender

<b>indotwittergender</b> merupakan repositori untuk menyimpan kode sumber yang digunakan dalam artikel yang berjudul <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a>. Jika Anda menggunakan beberapa komponen di dalam repositori ini, harap kutip artikel berikut:

```
@article{JIKI1079,
	author = {Rahmad Mahendra and Hadi Syah Putra and Douglas Faisal and Fadzil Rizki},
	title = {Gender Prediction of Indonesian Twitter Users Using Tweet and Profile Features},
	journal = {Jurnal Ilmu Komputer dan Informasi},
	volume = {15},
	number = {2},
	year = {2022},
	keywords = {gender; Twitter; user; classification; feature extraction; demography},
	abstract = {The increasing use of social media generates huge amounts of data which in turn triggers research into social media analytics. Social media contents can be analyzed to explore public opinion on an issue or provide the insights reflecting proxy indicators towards real-world events. Understanding the demographics of social media users can increase the potential for applications of sentiment analysis, topic modeling, and other analytical tasks. To map demographics, we need to know the latent attributes of users, such as age, gender, occupation and location of residence. Since this attribute is not directly available, we need to do some inference from the social media data. This study aims to predict the gender attribute given a Twitter user account. We conducted experiments with several supervised classifiers with feature extraction, including the use of word embedding representations. The results of this study indicate that the combination of features extracted from Tweet contents and user profile structured data can predict the gender of Twitter users in Indonesia with accuracy above 80%.},
	issn = {2502-9274},	pages = {131--141},	doi = {10.21609/jiki.v15i2.1079},
	url = {https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079}
}
```
# Repository structure
- example-data/
  - Ridwan Kamil profile data [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/example-data/df_structured.xlsx)
  - Ridwan Kamil tweet data [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/example-data/ridwankamil.csv)

- jupyter notebook/
  - Data Collection
    - Structured [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/jupyter-notebook/Data%20Collection%20(Structured).ipynb)
    - Tweet [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/jupyter-notebook/Data%20Collection%20(Tweet).ipynb)
  - Feature Extraction [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/jupyter-notebook/Feature%20Extraction.ipynb)
  - Predict using Gradient Boosting [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/jupyter-notebook/Predict%20using%20Gradient%20Boosing.ipynb)

- misc/
  - POS tagger [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/misc/all_indo_man_tag_corpus_model.crf.tagger)
    - Raw data [[Tautan]](https://github.com/famrashel/idn-tagged-corpus)
  - Emoticon [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/misc/EMOTICON.txt)

- model/
  - Gradient Boosting [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/model/Ablation%20bio_Gradient%20Boosting_train_test_split.sav)

- vectorizer/
  - Bio
    - All [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/bio_feat_bow_vec.pickle)
    - No stopwords [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/bio_feat_bow_stop_vec.pickle)
  - Name
    - All [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/name_feat_ia_vec.pickle)
    - Without last name [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/name_feat_ib_vec.pickle)
    - First name [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/name_feat_ic_first_vec.pickle)
    - Middle name [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/name_feat_ic_middle_vec.pickle)
    - Last name [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/name_feat_ic_last_vec.pickle)
  - Tweet
    - All [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/tweet_feat_bow_vec.zip)
    - No stopwords [[Tautan]](https://github.com/ir-nlp-csui/indotwittergender/blob/main/vectorizer/tweet_feat_bow_stop_vec.zip)
