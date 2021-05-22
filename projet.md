---
description: Gérer ses projet
---

# 🪴 Projet

## Ajouter :hashtag

Le **hashtag** est un mot seulement composé de lettre sans espace ni charactere speciaux, il servira a identifier ton projet et dois etre unique.

```text
/im projet ajouter hashtag: indiemaker
```

## Modifier :hashtag

Cela te permet de modifier ton compte Maker, voici les valeurs que tu peux modifier :

* **logo**: L'url vers le logo de ton projet
* **couverture**: L'url vers l'image de couverture de ton projet
* **emoji**: Un emoji qui représente ton projet
* **color**: Une couleur en [Hexa](https://www.color-hex.com/) pour ton projet
* **nom**: Le nom de ton projet
* **description**: La description de ton projet
* **website**: L'url de ton site perso \(avec https://\)
* **categorie:** La categorie de ton projet, les valeurs possible sont  :
  * Saas
  * Application
  * Communauté
  * Newsletter
  * Formation
  * Template
  * Ecommerce
  * Autre
* **stripe\_key**: Ta clé api [stripe](https://dashboard.stripe.com/apikeys)
* **github**: Lien vers l'url github du projet \(avec https://\)
* **open\_source**: Le projet est il open source?

  * Oui
  * Non

```text
/im projet modifier hashtag: indiemaker emoji: 🔥
```

{% hint style="warning" %}
Astuce: pour utiliser un champ clique dessus ou ecris son nom puis "**:**" et utilise la touche **TAB**
{% endhint %}

Les valeurs peuvent se cummuler :

```text
/im projet modifier hashtag: indiemaker emoji: 🔥 color: #fff
```

### Stripe\_key

La stripe key permet de recupéré automatique toute Les ventes passé sur ton projet pour les ajouter aux revenue.

Une fois l'initialisation faite, tes revenue serons mis a jours tous les lundi a 9h pour le mois en cours !  
Pour l'obtenir, vas ici :

{% embed url="https://dashboard.stripe.com/apikeys" %}

Crée une **Restricted keys :**

![](.gitbook/assets/screenshot-2021-05-12-at-16.07.25.png)

avec les droits **Charges** en lecture seule.

![](.gitbook/assets/screenshot-2021-05-12-at-16.07.59.png)

![](.gitbook/assets/screenshot-2021-05-12-at-16.08.45.png)

## Liste 

Cela te permet de voir la liste de tous tes projets

```text
/im projet liste
```

## Liste @Mention

Cela te permet de voir la liste de tous les projets d'un maker

```text
/im projet liste maker: @martindonadieu
```

## Voir :hashtag

Cela te permet de voir un projet qui t'appartiens

```text
/im projet voir hashtag
```

## Voir :hashtag @Mention

Cela te permet de voir un projet d'un autre maker

```text
/im projet voir hashtag: indiemakers maker: @martindonadieu
```

## Supprimer :hashtag

Cela te permet de supprimer un projet qui t'appartiens

```text
/im projet supprimer: indiemaker
```

