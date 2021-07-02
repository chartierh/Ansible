# Projet Ansible Stack Docker + LAMP

Créer un playbook ansible qui déploiera sur 3 machines :

* **infra1** : docker, gitlab (dans un container), un environnement de dev LAMP
* **web1** : 2 CMS
* **db1** : 2 DB (1/CMS)

## Utilisation

### Cloner le dépôt :

<code>git clone </code>

### Copier l'inventaire "modèle"

<code>cp inventory.dist inventory</code>

### Lancer le Playbook

<code>ansible-playbook -i inventory playbook.yml</code>
