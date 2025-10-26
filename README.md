# Operations_on_word_vectors
Ce projet explore la détection et la réduction des biais de genre dans les embeddings de mots (word embeddings).
Deux méthodes principales sont implémentées :

Neutralisation : Supprime la composante de genre pour les mots neutres.

Égalisation : Ajuste les paires de mots spécifiques au genre (comme acteur/actrice) pour les rendre symétriques autour de l’axe de genre, tout en conservant leurs différences sémantiques.

Ces techniques permettent de réduire les stéréotypes implicites dans les modèles de langage et d’obtenir des embeddings plus équitables.

Fonctionnalités

Neutralisation de mots neutres vis-à-vis du genre.

Égalisation des paires de mots spécifiques au genre.

Visualisation de l’effet de la neutralisation et de l’égalisation.

Calcul des similarités cosinus avant et après correction des biais.
