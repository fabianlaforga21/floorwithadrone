# Floor with a drone

Statische website (HTML/CSS/JS) — geen build-stap nodig.

## Bestanden
- `index.html` — homepage
- `contact.html` — contactpagina
- `styles.css` — alle styling
- `script.js` — mobiel menu + scroll-animaties

## Je eigen foto's plaatsen
Nu staan er tijdelijke placeholder-foto's in (via picsum.photos).
Vervang ze zo:
1. Maak een map `images/` aan en zet daar je eigen foto's in.
2. Zoek in `index.html` naar de `src="https://picsum.photos/..."` regels
   (er staat telkens een comment `VERVANG ...` boven) en vervang door
   bijvoorbeeld `src="images/water.jpg"`.
3. De achtergrondfoto van "How to book" zit in `styles.css` (zoek op `picsum`).

## Live zetten op GitHub Pages
1. Maak een nieuwe repository op GitHub (bv. `floor-with-a-drone`).
2. Upload deze bestanden in de root van de repo.
3. Ga naar **Settings → Pages**.
4. Kies bij *Source* de branch `main` en map `/ (root)`, klik **Save**.
5. Na ~1 minuut staat de site live op
   `https://<jouw-gebruikersnaam>.github.io/floor-with-a-drone/`.
