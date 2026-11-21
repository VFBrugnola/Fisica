# Fisica per la filosofia

**Materiali interattivi di fisica per l'insegnamento della filosofia al liceo.**

🔗 **Sito:** https://vfbrugnola.github.io/Fisica/

Non è un corso di fisica. Le simulazioni servono a far *vedere* agli studenti le idee dei filosofi della natura, dai presocratici a Galileo e Keplero, per discuterne il significato filosofico: che cosa esiste davvero, come nasce e muore ciò che cambia, che cosa è un esperimento, perché la natura si può descrivere con la matematica.

Ogni pagina unisce **teoria, fonti e simulazioni** nella stessa struttura:

- testo introduttivo e simulazione interattiva, con comandi e dati misurati;
- spiegazione di che cosa osservare;
- teoria con i frammenti e le fonti antiche, oppure le leggi con la legenda di ogni simbolo;
- riquadro **«Il punto filosofico»**.

Le simulazioni dei presocratici sono **modelli visivi** delle loro teorie, non ricostruzioni di calcoli: ogni pagina lo dichiara.

## Contenuti

### 00 · Fisica antica
| Pagina | Simulazioni |
|---|---|
| [**Empedocle**: le quattro radici](https://vfbrugnola.github.io/Fisica/antica/pluralisti/empedocle.html) | Amore e Contesa che mescolano e separano fuoco, aria, acqua e terra; ciclo cosmico |
| [**Anassagora**: i semi e il Nous](https://vfbrugnola.github.io/Fisica/antica/pluralisti/anassagora.html) | Lente a zoom senza fine (divisibilità infinita, «tutto in tutto»); vortice del Nous |
| [**Democrito**: atomi e vuoto](https://vfbrugnola.github.io/Fisica/antica/pluralisti/democrito.html) | Il coltello che si ferma all'atomo; atomi che si aggregano nel vuoto; il clinamen di Epicuro |

*In arrivo:* monisti, Parmenide e Zenone, Aristotele.

### 01 · Meccanica
| Pagina | Simulazioni |
|---|---|
| [**Galileo Galilei**: gli esperimenti](https://vfbrugnola.github.io/Fisica/meccanica/galileo/index.html) | Caduta dei gravi, piano inclinato, pendolo, due piani inclinati (inerzia), nave di Galileo, moto dei proiettili |
| [**Leggi di Keplero**](https://vfbrugnola.github.io/Fisica/meccanica/gravitazione/leggi-keplero/index.html) | Orbita ellittica, legge delle aree, legge dei periodi |

*In arrivo:* cinematica, dinamica, lavoro ed energia, quantità di moto.

### In arrivo
Termodinamica · Onde e ottica · Elettromagnetismo

## Come usarlo

- **Online:** basta aprire il [sito](https://vfbrugnola.github.io/Fisica/), funziona anche da telefono e alla LIM.
- **Offline:** scarica il repository (*Code → Download ZIP*) e apri `index.html` nel browser. Serve la connessione solo per caricare p5.js e KaTeX dalla CDN.

## Struttura

```
Fisica/
├── index.html                 home con i moduli
├── assets/css/style.css       stile unico per tutte le pagine
├── antica/pluralisti/         Empedocle, Anassagora, Democrito
└── meccanica/
    ├── galileo/               teoria + 6 esperimenti
    └── gravitazione/leggi-keplero/
```

## Tecnologie

- HTML e CSS, senza framework né build: sono pagine statiche pubblicate con GitHub Pages
- [p5.js](https://p5js.org/) per le simulazioni
- [KaTeX](https://katex.org/) per le formule

## Licenza

Questo lavoro è distribuito con licenza [Creative Commons Attribuzione – Non commerciale 4.0 Internazionale (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.it). Il testo completo è nel file [LICENSE](LICENSE).

Puoi usare, copiare, modificare e ridistribuire i materiali, per esempio in classe, **a condizione di citare l'autore**, indicare un link alla licenza e segnalare se hai apportato modifiche. **Non è consentito l'uso a scopo commerciale.** Esempio di citazione:

> «Fisica per la filosofia» di Fabrizio Brugnola (VFBrugnola), https://github.com/VFBrugnola/Fisica, licenza CC BY-NC 4.0.

Le librerie p5.js (LGPL 2.1) e KaTeX (MIT) restano soggette alle rispettive licenze. Le traduzioni dei frammenti antichi sono adattate e vanno confrontate con un'edizione di riferimento.
