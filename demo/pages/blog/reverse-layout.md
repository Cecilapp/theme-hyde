---
title: Reverse layout
date: 2026-08-12
tags: [Hyde, Configuration]
---
The page orientation can be reversed with a single option, to move the sidebar to the right.

<!-- excerpt -->

```yaml
hyde:
  reverse: true
```

By default, the sidebar content is stuck to the bottom of the sidebar. Disable this behavior with:

```yaml
hyde:
  sidebar:
    sticky: false
```
