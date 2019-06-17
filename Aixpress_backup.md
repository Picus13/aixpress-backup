---
marp: true
title: Introduction aux sauvegarde sur WP
description: Une présentation des objectifs de la sauvegarde & des bonnes pratiques
theme: default
paginate: true
footer: Présentation par [Julian](https://kappie.xyz) pour le Meetup Aixpress
---

# Introduction à la sauvegarde sur WordPress

Objectif de la sauvegarde & bonnes pratiques

![bg right 50%](./undraw_file_synchronization_8dh6.png)

---

<!--
_backgroundColor: #123
_color: #fff
-->

## <!--fit-->  Pourquoi sauvegarder ???

---

<!--
_backgroundColor: #123
_color: #fff
-->

### Pour pouvoir restaurer après :

* Une mise à jour qui plante 
* Une mauvaise manipulation
* Un Piratage du site
* L'hébergeur plus disponible
* ...
---

<!--
_backgroundColor: #123
_color: #fff
-->

### Ce qui vous apporte :

* Sérénité & paix intérieur
* Ca rassure vos prospects/clientéle
* Pas de stress cet été

---

<!--
_backgroundColor: #123
_color: #fff
-->

## <!--fit--> Quels fichiers sauvegarder ???

---

<!--
_backgroundColor: #123
_color: #fff
-->

### La réponse est simple :
* Les fichiers WP
    * *wp-content, wp-includes, wp-admin ...*
* Base de données SQL 

---

<!--
_backgroundColor: #123
_color: #fff
-->

## <!--fit--> Comment sauvegarder sur WP ???

---
 
<!--
_backgroundColor: #123
_color: #fff
-->

* Via FTP (long et fastideux si plusieurs site)
* Avec une extension WP 
* Un service tiers
* Via la ligne de commande
* Avec un script

---

<!--
_backgroundColor: #123
_color: #fff
-->

## <!--fit--> Les Bonnes Pratiques

---

<!--
_backgroundColor: #123
_color: #fff
-->

### Les + recommandés :
* Sauvagarde régulieres  *à adapter en fonction de la nature du site*
* Stockage multiple :
    * En local sur votre machine *attention à la panne*
    * Sur un stockage à chaud (Drive/Cloud)
    * Stockage à froid (Disque dur extene, Carte SD) *Utile pour l'archivage*
    
---

<!--
_backgroundColor: #123
_color: #fff
-->

### Combien de temps garder les sauvegardes :
* Le plus longtemps possible
* Selon ancienneté et nature du site, une sauvegarde mensuelle peût-être suffisante

---

<!--
_backgroundColor: #123
_color: #fff
-->

## <!--fit--> Conclusion

---

<!--
_backgroundColor: #123
_color: #fff
-->

### Recette de la parfaite sauvegarde :
* Automatisé : *Un script ou une extension fait le job pour vous*
* Stockage externe : *vos sauvegardes sont toujours accessibles*
* *Facultatif* : Un chiffrement peut-ête appliqué pour améliorer la sécurité de vos sauvegardes

    
---
## Merci de votre attention

Un peu de lecture :
* [Un article de Bruno Tritsch](https://brunotritsch.fr/bonnes-pratiques-wordpress-les-sauvegardes-sont-vos-amies/)
* [Choix d'extensions de sauvegarde par WP Marmite](https://wpmarmite.com/sauvegarder-wordpress/)
--

* [Dépôt de cette présentation](https://github.com/Picus13/aixpress-backup)
License : [WTFPL](https://choosealicense.com/licenses/wtfpl/)

![bg right 50%](./undraw_profile.png)