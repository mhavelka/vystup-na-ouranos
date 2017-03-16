
# Výstup na Ouranos

Larp Výstup na Ouranos. Struktura dokumentů:

- `texty/postavy` texty pro jednotlivé postavy a scény
- `texty/postavy-spolecny-uvod.md` kus textu sdílený mezi všechny duše
- `texty-en` obsahují anglický překlad, dokumenty jsou stejné jako v `texty`
- `sablony` obsahují podklady pro generování html (z nějž se následně generuje pdf)
- `nastroje` skripty zpracovávající texty a šablony a generující pdf

## Vytvoření pdf

Originální text používá font MS Calibri. Před vygenerováním zkopírovat `calibri.tff`, `calibrib.ttf` a další varianty do `sablony/postavy/fonty`. Následně:

```bash
make
```
Výsledný dokument se vytvoří v složce `vystupy`.

## TODOs

- převést v en postavách uvozovky na anglické (resp na ASCII a v konvertoru na anglické) a změnit hypenaci na anglickou
- vygrepovat TODO a opravit (vyskytuje se v textech)
- projít TODOs v příručce (mj. jaké dokumenty se mají generovat)
- generování příručky
- naformátovat en příručku
- v hudbě přejmenovat soubory a uklidit playlisty
- stahování z youtube, pokud lze
- udělat v readme en část
- zvážit nějaké synchro s google docs (ve smyslu make, který natáhne obsah veřejného gdocu do souboru)
