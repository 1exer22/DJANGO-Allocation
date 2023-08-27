# DJANGO-Allocation

Python : Django est un framework Python, donc vous devez avoir Python installé sur votre système. Django est compatible avec plusieurs versions de Python, mais il est recommandé d'utiliser une version prise en charge. Au moment de ma dernière mise à jour en septembre 2021, Django 4.2 prend en charge Python 3.6, 3.7, 3.8, 3.9 et 3.10.

Environnement virtuel (recommandé) : Il est fortement recommandé d'utiliser un environnement virtuel pour isoler les dépendances de chaque projet Django. Vous pouvez utiliser venv, virtualenv ou conda pour créer un environnement virtuel.

Django : Vous devez installer le framework Django à l'aide de pip (le gestionnaire de packages Python). Vous pouvez l'installer en exécutant la commande suivante dans votre environnement virtuel :

bash
Copy code
pip install django
Base de données : Django utilise une base de données pour stocker les données de votre application. Par défaut, il utilise SQLite, mais il prend également en charge d'autres bases de données telles que MySQL, PostgreSQL, Oracle, etc. Assurez-vous d'installer et de configurer la base de données que vous préférez.

Éditeur de texte / IDE : Vous aurez besoin d'un éditeur de texte ou d'un environnement de développement intégré (IDE) pour écrire et gérer votre code Django. Des options populaires incluent Visual Studio Code, PyCharm, Sublime Text, etc.

Navigateur Web : Vous aurez besoin d'un navigateur pour visualiser votre application web en cours d'exécution.

Une fois que vous avez configuré ces éléments, vous pouvez créer un nouveau projet Django à l'aide de la commande suivante (assurez-vous d'être dans le répertoire où vous souhaitez créer le projet) :

bash
Copy code
django-admin startproject nom_de_votre_projet
Ensuite, vous pouvez vous déplacer dans le répertoire du projet et exécuter le serveur de développement Django à l'aide de la commande :

bash
Copy code
python manage.py runserver
Cela lancera le serveur de développement de Django et vous pourrez accéder à votre application en utilisant l'adresse http://127.0.0.1:8000/ dans votre navigateur.

Veuillez noter que les versions et les détails peuvent changer avec les mises à jour, alors assurez-vous de vérifier la documentation officielle de Django pour les exigences spécifiques à la version que vous utilisez.
