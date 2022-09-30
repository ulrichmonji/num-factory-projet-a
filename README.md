# Industrialisation des gestes


## Contexte 
 Automatiser le déploiement d'une application 2 tiers (**Frontend** + **backend**)
### Le frontend
 Il pourait être un simple site statique, ou une appli php, python, nodejs, peu importe

### Le Backend 
Il pourrait être une Base de donnée mysql ou mariadb, ou même une API toute simple.



## Outils indispensables: 
- Ansible
- Vagrant
- Virtualbox
- Vmware workstation
- Linux (Shell Bash)

## Organisation du travail dans le temps
On a **8 Jours** de projet. Une proposition d'organisation du temps est la suivante : 

* Installation manuelle du produit + rédaction de la documentation
  * **Durée** : **2 jours**, du 3/09/2022 au 4/09/2022*
  *  **Outils** : *git*, *linux*, *bash*, *apache*, *php*, *python*, *mysql*, etc ...
  * **Ce qu'il faut faire** : L'idée est de faire abstraction de tout outil d'automatisation et se concentrer sur l'installation du produit en lui même. Ensuite il faudra réaliser une documentation d'installation du produit, qui ne fait intervenir aucun outil d'automatisation.
* Automatisation avec Ansible
  *  **Durée** : **4 Jours**, du 5/09/2022 au 10/09/2022
  *  **Outils** : *git*, *ansible*
  * **Ce qu'il faut faire** : Etant donné votre documentation d'installation rédigée à la précédente partie, il faudrait à présent développer un playbook ansible qui permet d'automatiser l'installation. 
* Integration des outils
  *  **Durée** : **1 Jour**, le **11/09/2022**
  *  **Outils** : *git*, *vagrant*, *virtualbox*, *vmware*, *bash*

  * **Ce qu'il faut faire** : A ce stade, vous avez un playbook ansible qui installe votre application. Cependant, le provisioning de votre infrastructure de travail n'est pas automatique. A l'aide de l'outil **vagrant**, il faudrait automatiser le provisioning de votre infrastructure, et une fois provisionné, vagrant laissera la main à votre playbook ansible pour déployer l'application. [Voici](https://www.youtube.com/watch?v=z4209uoIbmk&t=7376s&ab_channel=eazytraining) un tutoriel sur **vagrant**, et [ici](https://github.com/diranetafen/cursus-devops/tree/master/vagrant) vous trouverez des exemples de stack vagrant.
* Livrable et documentation du projet 
  *  **Durée** : **1 Jour**, le 12/09/2022
  *  **Outils** : *git*, *Markdown*
  * **Ce qu'il faut faire** : A ce stade, vous avez un projet complet. Votre application peut se déployer from scratch à l'aide d'une seule ligne de commande. Il est à présent question de fournir un livrable final contenant la documentation de votre projet. Ce livra devra : 
    * être présente sur un repos github ou gitlab
    * contenir l'ensemble des ressources nécessaires au déploiement de votre application
    * contenir un fichier Readme.md, redigé en Markdown, qui explique très clairement comment utilisé votre travail. [Voici](https://stackedit.io/) un site pour écrire du markdown facilement.
:warning:  

