# home-test-design

Codice della pagina **Home test design** di The Cape Studio (Webflow).

Qui sta solo il codice **nuovo o modificato** per la pagina di test. Gli script
originali restano nelle loro repo e non si toccano: se uno va cambiato, la sua
copia modificata finisce qui e la pagina di test carica la copia.

## File

| File | Cosa fa | Dove si carica |
|---|---|---|
| `ritocco.css` | Lo stile del ritocco: font, barra in alto, link… Vale a tutte le larghezze di schermo e solo sulla pagina di test. | Page settings → Custom code → Inside `<head>`, **in fondo** |

## Come si aggiorna

Ogni link usa il codice di una versione precisa (il pezzo dopo la `@`):

```
https://cdn.jsdelivr.net/gh/cash9086/home-test-design@<versione>/ritocco.css
```

Quando un file cambia, cambia anche il link: una modifica qui non tocca il
sito finché in Webflow non si incolla il link nuovo.

## Passi del ritocco

1. Font, barra in alto, link, cursore normale.
