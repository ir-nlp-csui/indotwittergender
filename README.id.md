# indotwittergender
<b>indotwittergender</b> merupakan repositori untuk menyimpan kode sumber yang digunakan dalam artikel yang berjudul <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a>. Jika Anda menggunakan beberapa komponen di dalam repositori ini, harap kutip artikel berikut:

*Baca README ini dalam [English](README.md).*

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

## Struktur repositori
    .
    ├── embedding-model
    │   ├── Fastext_model_tweet.bin
    │   ├── Word2Vec_400dim.txt
    │   └── fasttext.4B.id.300.epoch5.uncased.bin
    ├── example-data
    │   ├── df_structured.xlsx
    │   └── ridwankamil.csv
    ├── jupyter notebook
    │   ├── Data Collection (Structured).ipynb
    │   ├── Data Collection (Tweet).ipynb
    │   ├── Feature Extraction.ipynb
    │   └── Predict using Gradient Boosting.ipynb
    ├── misc
    │   ├── all_indo_man_tag_corpus_model.crf.tagger
    │   └── EMOTICON.txt
    ├── model
    │   └── Ablation bio_Gradient Boosting_train_test_split.sav
    └── vectorizer
        ├── bio_feat_bow_vec.pickle
        ├── bio_feat_bow_stop_vec.pickle
        ├── name_feat_ia_vec.pickle
        ├── name_feat_ib_vec.pickle
        ├── name_feat_ic_first_vec.pickle
        ├── name_feat_ic_middle_vec.pickle
        ├── name_feat_ic_last_vec.pickle
        ├── tweet_feat_bow_vec.zip
        └── tweet_feat_bow_stop_vec.zip
