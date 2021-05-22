---
description: Gérer son Compte
---

# 👨‍🌾 Maker

## Modifier 

Cela te permet de modifier ton compte Maker, voici les valeurs que tu peux modifier :

* **photo**: L'url vers ta photo
* **emoji**: Un emoji qui te représente
* **twitter**: Ton nom twitter
* **couverture**: L'url vers ta photo de couverture
* **couleur**: Une couleur en Hexa qui te ressemble
* **nom**: Ton nom de scène ! 
* **bio**: Ta bio, qui te décrit 
* **website**: L'url de ton site perso \(avec https://\)
* **github**: L'url de ton github perso \(avec https://\)
* **makerlog:** L'url de ton compte getmakerlog.com perso \(avec https://\)
* **wip**: L'url de ton compte wip.co perso \(avec https://\)
* **twitter**: L'url de ton compte twitter.com perso \(avec https://\)
* **nomadlist**: L'url de ton compte nomadlist.com perso \(avec https://\)
* **makerlog\_hook**: L'url de ton webhook [makerlog](https://getmakerlog.com/)
* **wip\_key**: Ton api key pour connecter ton compte [wip.co](https://wip.co/)

```text
/im maker modifier emoji: 👷‍♂️
```

{% hint style="warning" %}
Astuce: pour utiliser un champ clique dessus ou écris son nom puis "**:**" et utilise la touche **TAB**
{% endhint %}

### Makerlog\_hook

La Makerlog hook permet de envoyer automatique toute tes taches faites sur un projets dans [makerlog](https://getmakerlog.com/).   
Pour que ca marche tu dois avoir configurer les meme hashtag avec tes projets, et le projet doit etre déjaà crée .  
Pour l'obtenir cette url, rend toi ici :

{% embed url="https://getmakerlog.com/integrations/webhooks" %}

![](.gitbook/assets/screenshot-2021-05-12-at-16.06.07.png)

Crée une webhook sans projet, copy l'url et ajoute la a ton profil via le bot, cette URL ne seras jamais affiché dans ton profil public

### Wip\_key

La WIP key permet de envoyer automatique toute tes taches faites sur des projets dans [wip](https://wip.co/).   
Pour que ca marche tu dois avoir configurer les meme hashtag avec tes projets  
Pour l'obtenir, vas ici :

{% embed url="https://wip.co/api" %}

![](.gitbook/assets/screenshot-2021-05-12-at-16.04.55.png)

Et tu crée une webhook sans projet !

Copy l'api key et ajoute la a ton profil via le bot, cette Api key ne seras jamais affiché dans ton profil public

## Voir @Mention

Cela te permet de voir le karma d'un Maker

```text
/im maker voir @martindonadieu
```

## Liste

Cela te permet de voir la liste de tous les markers du server

```text
/im maker liste
```

## 🔥 Flammes

Cela te permet de voir le classement des 10 premiers markers, classé par flammes !  


{% hint style="danger" %}
Elle correspondent aux nombre de jours consecutif depuis le quel le maker poste des taches sur son projet, si il loupe un jour le bot feras repartir le compteur a Zero 😢.

Meme un taches qui prend 5 min par jours compte   
5\*365/60 = **30 heures** a la fin de l'année dédié a ton projet !
{% endhint %}

{% hint style="warning" %}
Chaque maker a un compteur global, plus un compteur de flammes par projet, pour qu'on se pousse a etre regulier sur chaque projet !
{% endhint %}

```text
/im maker flammes
```

