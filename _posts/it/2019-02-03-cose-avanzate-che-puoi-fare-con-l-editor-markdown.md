---
layout: post
title:  "Cose avanzate che puoi fare con l'editor Markdown"
locale: it
author: jane
categories: 
    - Jekyll
    - tutorial
tags: 
    - [featured]
    - estate
image: https://images.unsplash.com/photo-1528784351875-d797d86873a1?ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80
---
Ci sono molte cose avanzate che puoi fare con l'editor Markdown. Se hai già acquisito una certa familiarità con la scrittura in Markdown, potresti apprezzare alcuni suggerimenti più avanzati su ciò che puoi fare con Markdown!

Come per l'ultimo post sull'editor, ti consigliamo di modificare effettivamente questo post mentre lo leggi, così da poter vedere tutto il codice Markdown che stiamo usando.


## Formattazione speciale

Oltre al grassetto e al corsivo, puoi anche utilizzare altri tipi di formattazione speciale in Markdown quando necessario, ad esempio:

+ ~~barrato~~
+ ==evidenziato==
+ \*caratteri con escape\*


## Scrivere blocchi di codice

Ci sono due tipi di elementi di codice che possono essere inseriti in Markdown: il primo è inline, mentre l'altro è un blocco. Il codice inline viene formattato racchiudendo qualsiasi parola o frase tra backtick, `come questo`. Blocchi di codice più grandi possono essere visualizzati su più righe utilizzando tre backtick:

```
.my-link { text-decoration: underline; }
```

Se vuoi rendere il tutto ancora più sofisticato, puoi anche aggiungere l'evidenziazione della sintassi usando Rouge.


![walking]({{ site.baseurl }}/assets/images/8.jpg)

## Liste di riferimento

Un altro modo per inserire collegamenti in Markdown è utilizzare le liste di riferimento. Potresti voler usare questo stile di collegamento per citare materiale di riferimento in stile Wikipedia. Tutti i collegamenti sono elencati alla fine del documento, così puoi mantenere una separazione completa tra il contenuto e la sua fonte o riferimento.

## HTML completo

Forse la parte migliore di Markdown è che non sei mai limitato solo a Markdown. Puoi scrivere direttamente in HTML all'interno dell'editor Markdown e funzionerà esattamente come HTML di solito fa. Nessun limite! Ecco un codice di incorporamento YouTube standard come esempio:

<p><iframe style="width:100%;" height="315" src="https://www.youtube.com/embed/Cniqsc9QfDo?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe></p>
