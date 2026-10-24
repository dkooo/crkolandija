# Črkolandija

Preprosta slovenska spletna aplikacija za otroke približno od 4 do 7 let. Vsebuje slovensko abecedo, igro začetnih črk, risanje s prstom ali miško, povezovanje besed s slikami in sestavljanje kratkih besed. Prilagojena telefonu, tablici in računalniku. Brez namestitve, prijave, oglasov in zunanjih knjižnic.

## Objava na GitHub Pages

1. Ustvari repozitorij `crkolandija` in vanj dodaj vse datoteke iz te mape (index.html mora biti v korenu).
2. V Settings → Pages izberi Deploy from a branch, vejo `main`, mapo `/ (root)` in Save.
3. Po uspešni objavi je stran na `https://UPORABNISKO-IME.github.io/crkolandija/`.

Za lokalno uporabo odpri `index.html`. Za razvoj lahko zaženeš `python3 -m http.server 8000`.

## Opombe

Zvezdice in obiskane črke se shranjujejo v localStorage tega brskalnika. Brez strežnika in zbiranja osebnih podatkov. Če je shranjevanje onemogočeno, aplikacija deluje brez trajnega napredka. Pisanje je prosto sledenje tiskani črki in ne predstavlja avtomatskega preverjanja pisave. Govor je na voljo le, če ima naprava slovenski sistemski glas; sistemska govorna storitev lahko uporabi omrežje. Otroku pri učenju pomaga odrasli. Pomen slik je lahko zaradi prikaza emojijev med napravami nekoliko drugačen.
