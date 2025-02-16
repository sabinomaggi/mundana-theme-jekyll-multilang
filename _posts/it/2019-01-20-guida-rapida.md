---
layout: post
title:  "Guida rapida a Jekyll"
author: sal
categories: [ Jekyll, tutorial ]
image: assets/images/12.jpg
---

Se hai già un ambiente di sviluppo Ruby completo con tutte le intestazioni e RubyGems installati (vedi i requisiti di Jekyll), puoi creare un nuovo sito Jekyll eseguendo i seguenti comandi:

```ruby
# Installa i gem di Jekyll e Bundler tramite RubyGems
gem install jekyll bundler

# Crea un nuovo sito Jekyll in ./myblog
jekyll new myblog

# Entra nella tua nuova directory
cd myblog

# Costruisci il sito sul server di anteprima
bundle exec jekyll serve

# Ora vai su http://localhost:4000
```