Bienvenue dans Notre Tutoriel de présentation des liste de packages les Plus Utiles en Django par Catégorie 
  > ## Package Relative a la partie Admin de Django
 
 - # Django-admin-interface
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/35631521-64b0cab8-06a4-11e8-8f57-c04fdfbb7e8b.gif)
   
    django-admin-interface est une interface admin adaptable et personnalisable, basée sur un thème plat moderne, elle vous permet de         personnaliser le titre, le logo et les couleurs de l'administrateur en fonction de l'administrateur lui-même. Fenêtres contextuelles       remplacées par des modaux.

    #### Caracteristique de Admin-interface
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
    #### Exigences
      - Python 2.7, 3.4, 3.5, 3.6, 3.7
      - Django 1.7, 1.8, 1.9, 1.10, 1.11, 2.0, 2.1, 2.2
     
    #### Installation
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
       
      #### Thèmes optionnels
      Ce paquet est livré avec des thèmes optionnels, vous pouvez les installer à l’aide de la commande loaddata admin. Les thèmes             facultatifs sont activés lors de l'installation.
     
    Django theme (default):
    - Bootstrap theme:
    exécute ``` python manage.py loaddata admin_interface_theme_bootstrap.json```
    
    - Foundation theme:
    exécute ``` python manage.py loaddata admin_interface_theme_foundation.json```

    - Web Design Standards theme:
    exécute ``` python manage.py loaddata admin_interface_theme_uswds.json```
     
  #### Capture de DJango-admin Interface
  ##### Interface De Connexion
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/55c8d4ba-8df1-11e5-9568-00fdc987ede8.gif)
   
  ##### Tableau de Bord Admin Interface
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/dash.gif)
  
  ##### Gestion des thèmes administratifs
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/6cd1c342-8df1-11e5-928b-f22217474d3d.gif)

  ##### Personnalisation du thème administrateur
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/7350d942-8df1-11e5-9b28-f2f54c333cdc.gif)
   
  # django-material-admin
   ![ alt text](https://github.com/guindosaros/package/blob/master/ImagePackage/35631521-64b0cab8-06a4-11e8-8f57-c04fdfbb7e8b.gif)
   
  django-material-admine est une interface admin adaptable et personnalisable, basée sur un thème De mb Boostrap et permet de 
  personnaliser l'admin de Django
    
#### Installation
- Exécute la commande dans votre console ```pip install django-material-admin```
- Ajouter dans ```python  INSTALLED_APPS ``` Du Setting de Votre projet  ```python   django-material-admin  ```  Avant  ```python  django.contrib.admin ```
```python  
      INSTALLED_APPS = (
        'material.admin',
        'django.contrib.admin',
      )
  
```
