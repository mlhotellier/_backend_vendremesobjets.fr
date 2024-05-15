# Backend - Projet vendremesobbjets.fr

Ce dossier contient le code et les ressources nécessaires uniquement pour le backend du projet.

## Configuration du Front-End

Pour commencer, vous devrez récupérer les ressources pour le front-end

1. **Clonage du Code Frontend :** Le code pour l'application frontend est nécessaire pour faire fonctionner le backend. À partir de votre répertoire de travail, exécutez la commande suivante :

    ```bash
    git clone https://github.com/OpenClassrooms-Student-Center/go-fullstack-v3-fr.git
    ```

2. **Installation des Dépendances Frontend :** Accédez au répertoire `go-fullstack-v3-fr` et installez toutes les dépendances requises par l'application frontend en exécutant les commandes suivantes :

    ```bash
    cd go-fullstack-v3-fr
    npm install
    ```

3. **Démarrage du Serveur de Développement :** Après avoir installé les dépendances, lancez le serveur de développement en utilisant la commande :

    ```bash
    npm start
    ```

    Cela lancera le serveur de développement pour l'application frontend. Désormais, si vous accédez à http://localhost:4200, vous devriez voir l'interface utilisateur de l'application.

## Configuration du Back-End

Pour commencer, vous devrez récupérer les ressources pour le back-end

. **Clonage du Code Backend :** À partir de votre répertoire de travail, exécutez la commande suivante :

    ```bash
    git clone https://github.com/mlhotellier/_backend_vendremesobjets.fr.git
    ```

2. **Installation des Dépendances Backend :** Accédez au répertoire `_backend_vendremesobjets.fr` et installez toutes les dépendances requises par l'application frontend en exécutant les commandes suivantes :

    ```bash
    cd _backend_vendremesobjets.fr
    npm install
    ```

3. **Démarrage du Serveur de Développement :** Après avoir installé les dépendances, lancez le serveur de développement en utilisant la commande :

    ```bash
    npm start
    ```

    Cela lancera le serveur de développement pour l'application backend.

4. **Remplacer les valeurs `process.env.VALUE` :** Créez un fichier `.env` à la racine de votre projet et ajouter les valeurs :
- PORT=<port> // Par défault configuré sur 3000
- DB_URL=<url> // Sous la forme NAME.ID.mongodb.net/
- DB_ID=<id>
- DB_PASSWORD=<password>


## Contributions

Les contributions à ce projet sont les bienvenues. N'hésitez pas à créer une issue ou à soumettre une pull request si vous souhaitez contribuer.

---

Ce README sera mis à jour au fur et à mesure que le projet avance. Restez à l'écoute pour plus de mises à jour !