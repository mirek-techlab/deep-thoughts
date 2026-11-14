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

## Redakční zásady: Náboženství

Sekce `religion` má **srovnávací, otevřený a nekonfesní charakter**. Není zaměřena na jediné vyznání ani na prosazování určité víry.

- Zahrnovat rozmanité tradice: šamanské praxe (v konkrétním kulturním kontextu), keltské, slovanské a germánské předkřesťanské tradice, judaismus, křesťanství, islám, hinduistické a buddhistické tradice, taoismus, místní a domorodá náboženství a další směry.
- Nabízet jak samostatné karty, tak srovnání (mýty, rituály, kosmologie, etika, smrt, posvátno, vztah člověka k přírodě).
- Pečlivě rozlišovat dobové prameny, pozdější tradici, odbornou interpretaci a moderní rekonstrukci či novopohanství. Nepředkládat moderní konstrukce jako doloženou starověkou víru.
- Popisovat jednotlivé tradice věcně a s respektem; představovat také relevantní spory a rozdíly, bez předpokladu, že jsou všechna tvrzení historicky ověřitelná.
- Upřednostňovat pestrý výběr tradic v čase; nikdy automaticky nezužovat obsah na osobní preference uživatele.

## Hlubší tematické pokrytí: Lakotové a Apsáalooke (Crow)

Vedle širokého a vyváženého pokrytí světových náboženství věnovat Lakotům a Apsáalooke (Crow) pravidelně **podrobnější samostatné karty a tematické série**. Nepovažovat je za zaměnitelné „indiánské náboženství“, nezjednodušovat jednotlivé národy na minulost a neslučovat duchovní praxe bez dokladů.

### Lakotové
- Wakȟáŋ Tȟáŋka, příbuznost všech bytostí a význam místa, krajiny, bizona a posvátné dýmky.
- Příběh Pte Sáŋ Wiŋ (White Buffalo Calf Woman) a různé verze podání.
- Sedm posvátných obřadů, např. Inípi, Haŋbléčheyapi, Wiwáŋyaŋg Wačhípi; jejich smysl, historie a současnost, nikoliv návod k napodobování.
- Nicholas Black Elk, John (Fire) Lame Deer a další lakotští vypravěči; rozlišit autentický hlas, záznam a editaci překladatele.
- Současné lakotské komunity, proměny a náboženská svoboda.

### Apsáalooke / Crow
- Vlastní názvy, tradice a historický kontext národa Apsáalooke.
- Posvátný tabák, Tobacco Society a související adopční vazby, společenský a duchovní význam.
- Vidění, půst a osobní duchovní zkušenost; `baaxpée` v kontextu konkrétních zdrojů.
- Posvátné svazky (medicine bundles, `xapáalia`), význam vlastnictví, opatrování a omezení veřejného zobrazování.
- Sun Dance, společenská kontinuita a proměny obřadů; různé současné podoby víry.
- Plenty Coups, Joseph Medicine Crow a současné hlasy Apsáalooke.

### Metoda a etika
- V prvé řadě vyhledávat veřejně sdílené materiály příslušníků komunit, jejich kulturních institucí a odborné studie s jasným původem.
- Veřejné obřady vysvětlovat jako kulturní/religiózní praxi, nikoliv vydávat pokyny k provádění neveřejných či chráněných obřadů.
- Uvádět konkrétní zdroj a případné varianty i nejistoty. Nevydávat jeden zápis či vypravěče za hlas všech.
- Zachovávat pestrý program ostatních náboženství a témat Deep Thoughts.

### Výchozí veřejné zdroje
- Aktá Lakota Museum — Seven Sacred Rites: https://aktalakota.stjo.org/lakota-culture/seven-sacred-rites/
- Smithsonian National Museum of the American Indian — Lakota White Buffalo Calf Woman: https://americanindian.si.edu/nk360/plains-belonging/pdf/Plains_Question1_OcetiSakowin_WhiteBuffaloLameDeer_Excerpt.pdf
- Yale eHRAF — Crow ethnographic summary: https://ehrafworldcultures.yale.edu/cultures/nq10/summary
- Smithsonian NMAI — Apsáalooke Tobacco Society sacred bundle (image withheld): https://americanindian.si.edu/collections-search/object/NMAI_126125
