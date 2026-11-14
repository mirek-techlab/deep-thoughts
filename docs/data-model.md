# Deep Thoughts — datový model

## Zásady
- Tento GitHub repozitář je **veřejný**. Karty, poznámky i případný seznam oblíbených v něm jsou veřejně čitelné.
- ChatGPT konverzace se sem **automaticky nekopírují**.
- Osobní poznámky lze publikovat jen na výslovný pokyn uživatele.
- Nevkládat přihlašovací údaje, soukromé identifikátory ani citlivé údaje o jiných osobách.
- Každá karta má stabilní ID; citace a parafráze jsou rozlišené.
- Automatický zápis pravidelných vydání Po/St/Pá do repozitáře **zatím není propojen**.

## Souborové schéma
- `cards/<kategorie>/DT-NNNNNN.md`: karta s YAML front matter
- `notes/DT-NNNNNN.md`: osobní veřejné poznámky k dané kartě (vznikají až na pokyn)
- `library/favorites.json`: identifikátory veřejně označených oblíbených karet
- `index.json`: katalog pro vyhledávání a budoucí web

## Front matter karty
`id`, `title`, `author`, `category`, `tags`, `created`, `source`, `quote_type`, `status`.

Při přidání karty je nutné aktualizovat `index.json`. Historie změn je dostupná v Git historii.

## Zobrazování v ChatGPT
- V uživatelském rozhraní zobrazovat **název karty**, nikoliv interní ID typu `DT-000002`.
- ID zachovat pro vazby mezi soubory, odkazy, oblíbenými a poznámkami; uživatel jej nemusí znát.
- Vyhledávání podle názvu, autora, témat a obsahu.
- Příklady vysvětlovat pestře napříč běžným životem (vztahy, historie, rozhodování, finance, kultura, věda, technologie); neupřednostňovat profesní obor uživatele.
