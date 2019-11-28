Bienvenue dans Notre Tutoriel de présentation des liste de packages les Plus Utiles en Django par Catégorie 
  > ## Package Relative a la partie Admin de Django
 
 - ## Django-admin-interface
  
    django-admin-interface est une interface admin adaptable et personnalisable, basée sur un thème plat moderne, elle vous permet de         personnaliser le titre, le logo et les couleurs de l'administrateur en fonction de l'administrateur lui-même. Fenêtres contextuelles       remplacées par des modaux.

    ### Caracteristique de Admin-interface
    - Beau thème par défaut de Django
    - Gestion et personnalisation des thèmes (vous pouvez personnaliser le titre, le logo et les couleurs de l'administrateur)
    - Liste déroulante des filtres de liste (facultatif)
      NOUVEAU Modal associé (au lieu de l'ancienne fenêtre popup, optionnel)
    - NOUVEAU nom / marqueur de l'environnement
    - NOUVEAU sélecteur de langue
    - Optimisations de compatibilité / style pour:
      *  ```python django-ckeditor ```
      * ```python django-dynamic-raw-id ```
      * ```python traduction django-model ```
      * ```python django-tabbed-admin ```
      * ```python sorl-thumbnail ```
    ### Exigences
      - Python 2.7, 3.4, 3.5, 3.6, 3.7
      - Django 1.7, 1.8, 1.9, 1.10, 1.11, 2.0, 2.1, 2.2
     
    ### Installation
     - Exécute la commande dans votre console ```python  pip install django-admin-interface ```
     - Ajouter dans ```python  INSTALLED_APPS ``` Du Setting de Votre projet  ```python  admin_interface , flat_responsive, flat,               colorfield ```  Avant  ```python  django.contrib.admin ```
      ```python  
        INSTALLED_APPS = (
                  #...
                  'admin_interface',
                  'flat_responsive', # seulement si version django < 2.0
                  'flat', # seulement si version django < 1.9
                  'colorfield',
                  #...
                  'django.contrib.admin',
                  #...
               )
  
      ```
      - Ensuite exécute Les Commande suivante 
        * exécute ```python python manage.py migrate ```
        * exécute ```python python manage.py collectstatic ```
        * Redémarrez votre serveur 
       
      ## Thèmes optionnels
      Ce paquet est livré avec des thèmes optionnels, vous pouvez les installer à l’aide de la commande loaddata admin. Les thèmes             facultatifs sont activés lors de l'installation.
     
    Django theme (default):
    - Bootstrap theme:
    exécute ```python python manage.py loaddata admin_interface_theme_bootstrap.json```
    
    - Foundation theme:
    exécute ```python python manage.py loaddata admin_interface_theme_foundation.json```

    - Web Design Standards theme:
    exécute ```python python manage.py loaddata admin_interface_theme_uswds.json```
 
