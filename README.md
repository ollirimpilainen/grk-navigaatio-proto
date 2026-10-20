# GRK ja KSBR · navigaatioprototyyppi

Klikattava prototyyppi grk.fi:n ja ksbr.fi:n uudesta navigaatiosta. Molemmat sivustot rakennetaan samalla alustalla ja samoista lohkoista, joten prototyypissä voi vaihtaa sivustoa yläpalkista.

Prototyyppi on yksi tiedosto, `index.html`, eikä vaadi build-vaihetta. Se on julkaisupeili esittelyä varten eikä näy hakukoneissa (`noindex` ja `robots.txt`).

## Mitä prototyypissä on

- **Desktop:** ylävalikko, pudotusvalikot ja Palvelut-megavalikko (KSBR:llä Toimialat). Esc ja klikkaus valikon ulkopuolelle sulkevat valikon.
- **Mobiili** (alle 1180 px): Valikko-painike ja tasoittain porautuva valikko, jossa Takaisin ja hubilinkki.
- **Sivunäkymä:** murupolku, tuleva URL, sivun tila ja sen alasivut kortteina. KSBR:n sivuilla, joista on hi-fi-versio, on linkki [KSBR-prototyyppiin](https://ollirimpilainen.github.io/ksbr-proto/).
- **Osoitteet:** jokaisella sivulla on oma osoite (`#grk:/palvelut/` tai `#ksbr:/toimialat/`), joten sivuun voi linkittää suoraan.

## Merkinnät

- **Suunniteltu kankaalle:** sivu on Design-kankaalla.
- **Rakenteessa:** sivu on IA:ssa, mutta sitä ei ole vielä suunniteltu.
- **Osio sivulla:** ankkuri toisella sivulla, ei omaa sivua.
- **Uusi:** sivua ei ole nykyisellä sivustolla.

## Lähteet

Rakenne tulee dokumentista GRK · IA, sivukartta ja navigaatio (v6 ja 17.10.2026 tehdyt muutokset) sekä KSBR:n IA v1.3:sta. Muutokset 17.10.2026: GRK:n toimialoihin tuli Kaupungit ja väylät, ja Tietopankkia ei tehdä kummallekaan sivustolle. KSBR:n Ajankohtaista on KSBR-valikossa.

Muutokset 20.10.2026: palvelut ovat liiketoimintasivun palvelukortteja (osioita), eivät omia sivuja, eikä Menetelmät-sivua tehdä. Laatu, turvallisuus ja kalusto on nyt Laatu ja turvallisuus. Vastaanottopaikat, Laatu ja turvallisuus, Vastuullisuus ja Avoimet työpaikat on suunniteltu kankaalle.

Rakenteen muutos tehdään `index.html`:n `SITES`-puuhun.
