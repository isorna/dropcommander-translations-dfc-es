---
title: 'Dropzone Commander'
excerpt: 'Reglas de Dropzone Commander.'
position: 0
---

# Dropzone Commander

<script setup>
  import { data as pages } from '/documents.data'
  const slug = '/es/dzc/'
  const filteredPages = pages.filter(page => page?.href.indexOf(slug) > -1)
  const selectedPages = [
    filteredPages.find(page => page.href == `${slug}contents.html`),
    filteredPages.find(page => page.href == `${slug}earth-2673.html`),
    filteredPages.find(page => page.href == `${slug}rules/`),
    filteredPages.find(page => page.href == `${slug}scenarios/`),
    filteredPages.find(page => page.href == `${slug}building-your-army.html`),
    filteredPages.find(page => page.href == `${slug}special-rules.html`),
    filteredPages.find(page => page.href == `${slug}glossary.html`),
    filteredPages.find(page => page.href == `${slug}faq.html`),
  ]
</script>

<CategoryCardsContainer :pages="selectedPages" />
