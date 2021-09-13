---
description: Gérer les taches de son projet
---

# 💗 Tache

## Ajouter :hashtag

Cela te permet d'ajouter une tache, a un projet .

Par default les tache sont crée en status "Fait" si tu ne precise pas.

* **hashtag**: L'identifiant unique de ton projet
* **contenue**: Une description de la tache réalisé
* **status**: Le Status de la tache, il peut etre:
  * A faire
  * Fait

```text
/im tache ajouter hashtag: indiemakers contenue: Mise a jours de la doc
```

## Modifier :hashtag :Id

* **hashtag**: L'identifiant unique de ton projet
* **id**: L'identifiant unique de la tache

Cela te permet de modifier une tache d'un projet, voici les valeurs que tu peux modifier :

* **contenue**: Une description de la tâche réalisée
* **status**: Le Status de la tache, il peut être:
  * À faire
  * Fait

```text
/im tache modifier hashtag: indiemakers id: 0 contenue: Mise a jours de la doc
```

## Liste :hashtag

Cela te permet de voir la liste de toutes tes tâches par projet

```text
/im tache liste hashtag: indiemakers
```

## Liste :hashtag @Mention

Cela te permet de voir la liste de toutes les tâches d'un projet d'un Maker.

```text
/im tache liste hashtag: indiemakers maker: @martindonadieu
```

## Supprimer :hashtag :id

Cela te permet de supprimer une tache d'un projet qui t'appartient

```text
/im projet supprimer hashtag: indiemaker id: 0
```

