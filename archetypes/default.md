---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: '{{ .Date }}'
draft: true
description: 'Provided to search engines, can be used in listing pages' 

categories: ["no category"]
keywords: [] # ist nur für die Suchmaschienen, wird sowieso aus categories und tags befüllt
tags: ["2024"]

# Hugo will not publish content when:
#
#The draft value is true
#The date is in the future
#The publishDate is in the future
#The expiryDate is in the past
publishDate: {{ .Date }}
#expiryDate: {{ .Date }}

---

# Überschrift Größe 1 <!-- Größe wie Titel -->
## Überschrift Größe 2 <!-- Diese wird im TOC benutzt-->
### Überschrift Größe 3 <!-- Diese wird im TOC benutzt -->
#### Überschrift Größe 4
##### Überschrift Größe 5

This is **bold** text, and this is *emphasized* text.

* List Element
  * Eingerücktes List Element
  1) Nummeriert

<!-- Linien --> 

---
*** 

> Ein Zitat khkhku
> hkukh
> kuhkukuh

    noch ein Zitat  kj k

[Saal Digital Shop](https://www.saal-digital.de/photo-lulu)

[Shopify Merchandise](https://www.shopify.com/photo-lulu "Hier gehts zu meinen Artikeln bei Shopify")
