# 📝 To-Do List App

Application de gestion de tâches développée en **Vanilla JavaScript**

## 🚀 Fonctionnalités
- Ajouter/supprimer des tâches
- Marquer comme complétées/inachevées
- Persistance des données (localStorage)
- Compteurs dynamiques

## 🧠 Persistance
- Les tâches enregistrées dans le localStorage seront toujours disponibles
- L'application chargera automatiquement les tâches au chargement de la page

## ⚠️ Point à considérer
- Une fois une tâche supprimée, elle ne sera plus disponible (aucune récupération possible)
- Si le navigateur est réinitialisé, toutes les tâches seront perdues
- Si vous exécutez `localStorage.clear()` dans votre console, toutes les tâches seront supprimées

## 🧯 Dépannage
Si l'application ne fonctionne plus correctement, essayez les étapes suivantes :
- Mettez à jour votre navigateur
- Sauvegardez vos tâches manuellement :
  1. Exécutez dans la console :
   ```js
   console.log(JSON.parse(localStorage.getItem("task")));
   ```
   2. Copiez les données affichées dans un fichier `.txt` 
   3. Exécutez :
    ```js
   localStorage.clear() 
   ```
   pour réinitialiser l'application

   4. Réinsérez vos données manuellement si besoin
- Si le problème persiste laissez-moi un commentaire sur le [dépôt GitHub](https://github.com/Dioman-Keita/To-Do-List-App)

## 🛠️ Technologies utilisées
- JavaScript (ES6 modules)
- HTML5
- CSS3
- localStorage

## 📦 Aperçu
![To-Do List App](./screenshots/image.png)
![To-Do List App](./screenshots/image-2.png)
![To-Do List App](./screenshots/image-3.png)

## 📖 Utilisation
Commencez par ouvrir le fichier `index.html` dans votre navigateur. Ensuite vous pourrez ajouter, supprimer et modifier le statut d'une tâche. Pour ce faire suivez les étapes suivantes :

**Ajouter une tâche**

Entrez le nom de la tâche puis cliquez sur "Enregistrer"

**Modifier son état**

Cliquez sur `achevée` ou `inachevée` pour changer le statut

**Supprimer**

Cliquez sur `supprimer`

## Installation
```bash
git clone https://github.com/Dioman-Keita/To-Do-List-App
cd To-Do-List-App
```

### Pour le développement local :
Si vous  êtes en local installer Live server :
```bash
npm install -g live-server
live-server
```

## 📄 Licence
Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
