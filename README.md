# Le fameux tools qu'il a crée est en réalité un grabber
### 📖 Description
Son fameux tools ou il y'a un fichier src comprend un .exe ce qui est bizarre car normalement une source nous devons avoir accès à la totalité du code. De plus il utilise de nombreux module inutile pour un searcher dans snusbase qui devrait normalement comprendre : fade, requests, colorama, datetime et subprocess. 


### ⚙️ Fonctionnalités
- Récupération des informations du système (CPU, mémoire, disque) avec `psutil`
- Collecte des données réseau locales et de l'activité réseau
- Extraction d'informations du navigateur (cookies, historiques)
- Capture d'événements clavier avec `keyboard`
- Téléchargement et interaction avec des pages web via `selenium`
- Support des requêtes HTTP pour interagir avec des API externes avec `requests` et `httpx`

### 📦 Modules Utilisés

| Module          | Utilisation                                                                             |
|-----------------|-----------------------------------------------------------------------------------------|
| `requests`      | Effectuer des requêtes HTTP pour envoyer les données collectées vers un serveur distant. |
| `psutil`        | Récupérer des informations sur le système (CPU, RAM, processus, réseau, etc.).           |
| `fade`          | Ajouter des effets visuels et des couleurs dans le terminal lors de l'exécution.         |
| `selenium`      | Automatiser les actions sur le navigateur (récupération de cookies, historiques).        |
| `bs4`           | Parser des pages web et extraire des données spécifiques lors de la navigation.          |
| `colorama`      | Ajouter de la couleur dans la console pour une meilleure lisibilité des messages.        |
| `pycryptodome`  | Chiffrer ou déchiffrer les données sensibles avant de les envoyer ou stocker.            |
| `pypiwin32`     | Interagir avec des API spécifiques à Windows pour récupérer des informations système.    |
| `PIL-Tools`     | Manipuler des images locales si nécessaire.                                              |
| `pyinstaller`   | Convertir le script Python en un exécutable autonome pour une distribution facile.       |
| `keyboard`      | Capturer les événements du clavier pour suivre l'activité utilisateur.                   |
| `httpx`         | Effectuer des requêtes HTTP asynchrones pour une performance améliorée.                  |

## N'installez surtout pas son tools vous vous verrez steal 
