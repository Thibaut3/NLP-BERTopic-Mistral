# NLP-BERTopic-Mistral

Ce projet explore l'application de la modélisation thématique (topic modeling) à l'aide de BERTopic et du modèle de langage Mistral pour analyser le dataset "book-genre-prediction".

## Fonctionnalités

* **Modélisation Thématique avec BERTopic :** Utilise BERTopic pour extraire des thèmes significatifs à partir des résumés de livres.
* **Intégration de Mistral :** Exploite la puissance du modèle Mistral pour la génération de descriptions de thèmes ou pour l'amélioration des embeddings.
* **Analyse du Dataset `book-genre-prediction` :** Traite un dataset contenant des résumés de livres et leurs genres associés.
* **Visualisation des Thèmes :** Possibilité d'inclure des visualisations des thèmes découverts.

## Utilisation

1.  Le notebook nlp-topic-modeling-mistral contient les cellules à executer.
  
2.  Le résultat est disponible dans le fichier topic_visualization.html

3.  **Dataset :** Le dataset `book-genre-prediction` es disponible sur kaggle https://www.kaggle.com/datasets/athu1105/book-genre-prediction.

4.  **Modèle Mistral :**
    * Si vous utilisez un modèle Mistral via Hugging Face Transformers, assurez-vous d'avoir votre clé API Hugging Face configurée.
    * Si vous utilisez une version locale de Mistral (par exemple, un fichier `.gguf` avec `llama-cpp-python`), placez le fichier du modèle dans un répertoire désigné (par exemple, `models/`) et ajustez le chemin dans le code.

## Dataset

Le dataset `book-genre-prediction` contient typiquement deux colonnes principales :
* `summary` : Le résumé du livre.
* `genre` : Le genre littéraire du livre.

Nom : \`Votre Nom\`

## Licence

Ce projet est sous licence \`[Nom de la licence, par exemple, MIT]\`.
