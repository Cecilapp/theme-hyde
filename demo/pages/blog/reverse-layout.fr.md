---
title: Mise en page inversée
date: 2026-08-12
tags: [Hyde, Configuration]
---
L'orientation de la page peut être inversée avec une simple option, pour placer la barre latérale à droite.

<!-- excerpt -->

```yaml
hyde:
  reverse: true
```

Par défaut, le contenu de la barre latérale est fixé en bas. Désactivez ce comportement avec :

```yaml
hyde:
  sidebar:
    sticky: false
```
