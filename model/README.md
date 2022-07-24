# Model
The best model described in this research <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a> is Gradient Boosting. We provide the [example script](../jupyter-notebook/Predict%20using%20Gradient%20Boosting) of how to leverage the [model](Ablation%20bio_Gradient%20Boosting_train_test_split.sav). Features used as the input to the model are:
- Color: all
- Name: BoW with name dictionary
- Username: 3-5 chargram
- Network: #likes is ablated
- Behavior: #mention is ablated
- Socio: #verb is ablated
- Tweet: BoW without stopwords 

---

# Model
Model terbaik yang dijelaskan dalam riset <a href="https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1079">Gender Prediction of Indonesian Twitter Users Using Tweet and Profil Features</a> merupakan Gradient Boosting. Kami menyediakan [contoh *script*](../jupyter-notebook/Predict%20using%20Gradient%20Boosting) cara menggunakan [model](Ablation%20bio_Gradient%20Boosting_train_test_split.sav). Fitur-fitur yang digunakan sebagai input model adalah:
- Color: semua
- Name: BoW dengan kamus nama
- Username: 3-5 chargram
- Network: #likes dihilangkan
- Behavior: #mention dihilangkan
- Socio: #verb dihilangkan
- Tweet: BoW tanpa *stopwords* 
