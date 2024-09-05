---
title: 'Constructor de flotas'
excerpt: 'Constructor de flotas de Dropfleet Commander.'
position: 10
---

# {{ $frontmatter.title }}

<script setup>
  import { data as api } from '/es.dfc.api.data'
  const view = 'full'
  const name = 'Toulon'
</script>

Puedes construir tu propia flota usando el [Fleet Builder de TTCombat](https://dropfleetcommander.com/builder).

## Experimental

De mientras terminamos de desarrollar nuestro propio constructor de flotas, puedes usar estas plantillas para imprimir tu flota:

<ShipCard :api="api" :name="name" :view="view" />
