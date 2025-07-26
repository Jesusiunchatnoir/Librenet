# Forum CNT-AIT - Application Flutter

## 📱 Application Forum

Cette application Flutter reproduit l'interface d'un forum syndical avec :

### ✅ Fonctionnalités implémentées :
- **Navigation par onglets** (Forum / Profil)
- **Liste des discussions** avec titre, auteur, date, compteurs
- **Détail des posts** avec réponses
- **Création de nouveaux posts**
- **Profil utilisateur** avec statistiques
- **Design CNT-AIT** (couleurs rouge syndical)

### 🎨 Interface :
- **Écran Forum** : Liste des discussions, bouton flottant pour créer
- **Détail Post** : Contenu complet + réponses + zone de saisie
- **Création Post** : Formulaire titre/contenu avec validation
- **Profil** : Avatar, stats, paramètres

### 🚀 Pour lancer :
```bash
cd forum_app
flutter run
```

### 📂 Structure :
```
lib/
├── main.dart              # App principale + navigation
├── models/
│   └── post.dart         # Modèle de données
└── screens/
    ├── forum_screen.dart      # Liste des discussions
    ├── post_detail_screen.dart # Détail + réponses
    ├── create_post_screen.dart # Création post
    └── profile_screen.dart     # Profil utilisateur
```

L'application est fonctionnelle et affiche correctement l'interface du forum avec toutes les fonctionnalités de base.# Librenet
