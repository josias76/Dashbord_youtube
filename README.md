# 📊 YouTube Channel Dashboard

Ce projet est une application **Streamlit** interactive permettant de visualiser les statistiques d'une chaîne YouTube à partir d'un fichier de données `.csv`. Il offre une vue complète des performances de la chaîne (vues, heures de visionnage, abonnés, likes, commentaires, partages) sur différentes périodes (quotidienne, hebdomadaire, mensuelle, trimestrielle).

## 🚀 Fonctionnalités

- Tableau de bord interactif avec visualisation des métriques clés.
- Agrégation automatique des données par jour, semaine, mois ou trimestre personnalisé.
- Affichage des deltas et des pourcentages d’évolution.
- Filtres de date personnalisés.
- Affichage de graphiques de type *bar chart* ou *area chart*.
- Aperçu du DataFrame filtré.
- Détection des périodes incomplètes.

## 📁 Fichiers requis

Le fichier principal requis est :

- `youtube_channel_data.csv` : fichier contenant les données brutes de la chaîne YouTube. Il doit contenir au minimum les colonnes suivantes :
  - `DATE`
  - `SUBSCRIBERS_GAINED`
  - `SUBSCRIBERS_LOST`
  - `VIEWS`
  - `WATCH_HOURS`
  - `LIKES`
  - `COMMENTS`
  - `SHARES`

## 🛠️ Technologies utilisées

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Datetime](https://docs.python.org/3/library/datetime.html)

## ▶️ Lancer l'application

Assure-toi d'avoir installé les dépendances requises :

```bash
pip install streamlit pandas
```

Puis lance l'application :

```bash
streamlit run app.py
```

> Remplace `app.py` par le nom réel de ton fichier si nécessaire.

## 🧩 Arborescence du projet

```
youtube-dashboard/
│
├── app.py                    # Code principal de l'application
├── youtube_channel_data.csv # Données d'entrée
├── images/
│   ├── streamlit-logo-primary-colormark-lighttext.png
│   └── streamlit-mark-color.png
└── README.md                 # Ce fichier
```

## 👤 Auteur

Développé par **Josias Nteme**  
© 2025 – Tous droits réservés.

---

> Pour toute question ou suggestion d'amélioration, n'hésitez pas à me contacter !