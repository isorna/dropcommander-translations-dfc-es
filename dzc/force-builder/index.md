---
title: 'Constructor de ejércitos'
excerpt: 'Constructor de ejércitos de Dropzone Commander.'
position: 9
---

# {{ $frontmatter.title }}

<script setup>
  import { data as api } from '/es.dzc.api.data'
  const view = 'full'
  const name = 'Resistance Fighters'
</script>

Puedes construir tu propio ejército usando el [Force Builder de TTCombat](https://dropzonecommander.com/forcebuilder).

<TroopCard :api="api" :name="name" :view="view" />
