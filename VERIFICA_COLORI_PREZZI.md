# Verifica colori di prezzo e acquisto

Aggiornamento del 25 ottobre 2026.

| Elemento | Testo | Sfondo | Contrasto |
| --- | --- | --- | ---: |
| Prezzo finale | `#006D77` | `#FFFFFF` | 6,08:1 |
| Prezzo precedente barrato | `#667085` | `#FFFFFF` | 4,97:1 |
| Badge risparmio e sconto | `#102B3A` | `#F2A23A` | 7,00:1 |
| Pulsante primario in hover | `#FFFFFF` | `#0B676B` | 6,63:1 |
| Pulsante disabilitato | `#5A6769` | `#E9EEEF` | 5,01:1 |
| Pulsante secondario in hover | `#00545B` | `#DFEEEE` | 7,28:1 |

I rapporti superano il requisito WCAG AA di 4,5:1 per il testo normale. Il rosso `#B42318` resta riservato a errori, indisponibilità e scadenze reali; in queste pagine non identifica il prezzo scontato.

Le regole sono centralizzate in `template.css` e si applicano alle card dei bundle e alle relative pagine di dettaglio, compresi gli stati hover e disabled. Prezzi, percentuali e composizioni delle offerte non sono stati modificati.
