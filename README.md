# Citation styles

Formatul de bibliografie si citatii pentru lucrarile din Sesiunea de Comunicari Stiintifice al AII este derivat din stilul APA (American Psychological Association), cu numerotare stil IEEE.

In modelul AII formatul este:
[[./screenshot-exemplu-poli.png]]

Stilul din `./politehnica-bucuresti-apa-derived.csl` arata asa:
[[./screenshot-exemplu-zotero-preview.png]]

Stilurile sunt specificate utilizand CSL - Citation Style Language.

Am creat un `.csl` care sa reflecte cerintele de formatare date de AII.

Sursele jurnalelor cunoscute sunt disponibile in format CSL aici: https://github.com/citation-style-language/.

Din `apa.csl` am derivat `politehnica-bucuresti-apa.csl`, care folosete ca referinta formatul din ieee.csl `[1]` si bibliografia in stilul APA, la care am adaugat indexul ca `1. `.


### despre csl
Elementele care definesc formatul se gasesc de obicei la [finalul documentului](https://github.com/citation-style-language/styles/blob/b8070a75b46cdf0d0c14ebc9ff17c284ebc92d09/ieee.csl#L317-L511) .csl. Acestea sunt:

* `<citation>` -- pentru formatul referintei din text, in cazul IEEE este "[1]"
* `<bibliography>` -- pentru formatul intrarilor din bibliografia de la finalul documentului.


### cum aplic stilul
Folosesc [Zotero](https://zotero.com), unde stochez PDF-uri, site-uri pe care vreau sa le referentiez, etc. 

Zotero are pluginuri pentru LibreOffice, google docs, etc.. si permite selectarea stilului de citatie precum si cautarea si inserarea citatiilor din bibliografia locala. Recomand!

Tips despre cum sa editezi/folosesti stiluri pentru bibliografie: https://www.zotero.org/support/dev/citation_styles/style_editing_step-by-step
