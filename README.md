# Chassagne minimal

Démarrage une instance de Chassagne avec le minimum.

Choisir le sous-domaine de l'instance souhaité afin de gérer les URL d'accès.

Attention, lors du démarrage en mode `create`, penser à redémarrer en `update` une fois le premier lancement correctement effectué.

* [Chassagne](http://${SUBDOMAIN}.chassagne-qa.generixgroup.com) et [Chassagne-front](http://${SUBDOMAIN}-front.chassagne-qa.generixgroup.com)
* MySQL, inacessible en distant
* Mongo, inacessible en distant
* [File Manager](http://${SUBDOMAIN}-file.chassagne-qa.generixgroup.com), exécuter un *shell* pour faire un `backup`, un `restore` ou afficher la `list`
