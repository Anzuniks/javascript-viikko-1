# JavaScript Recap – Kaikki osiot (1–5)

Tämä repositorio sisältää JavaScript-kurssin kaikki kertaustehtävät (osiot 1–5). Projekti on jaettu selkeisiin osioihin, jotka kattavat:
- kielen perusteet
- DOM-manipulaation
- tapahtumankäsittelyn
- modernin AJAX / fetch -pohjaisen tiedonhakulogiikan
- (Recap 5) ravintolasovelluksen Metropolian ravintola-API:lla

---

## Tehdyt tehtävät ja kansiorakenne

### Recap 1 & 2: Perusteet
**Sijainti:** `/recap1` ja `/recap2`

**Sisältö:** muuttujat, ehtolauseet, taulukot ja funktioiden perusteet.

---

### Recap 3: DOM Assignments
**Sijainti:** `/recap3/dom-assignments/`

**Sisältö:**
- HTML-elementtien dynaaminen luominen (mm. `insertAdjacentHTML` ja DOM-metodit)
- BOM-rajapintoja
- Geolocation-paikannus
- Leaflet.js-karttojen integrointi

---

### Recap 4: Event Handling
**Sijainti:** `/recap4/event-assignments/` (tai vastaava)

**Sisältö:**
- tapahtumankäsittelyn perusteet
- event listenerien käyttö
- interaktiivisten UI-komponenttien toteutus

---

### Recap 5: AJAX Basics & Restaurant App (34 p)
Tässä osiossa hyödynnetään Reqres-testirajapintaa sekä Metropolian omaa ravintola-API:a.

**Sijainti:** `/recap5/` (tehtävät t1–t5)

**Tehtävät:**
- **t1 & t2:** GET- ja POST-metodien käyttö API-avaimen kanssa
- **t3:** edistynyt virheidenhallinta (`try/catch`) ja HTTP-statustunnistus
- **t4:** yleiskäyttöisen ja virheenkestävän `fetchData`-funktion kehittäminen
- **t5:** ravintolasovellus:
  - listaa Metropolian ravintolat
  - mahdollistaa aakkosjärjestyksen
  - hakee päivän menun dynaamisesti modaaliin

---

## Työkalut ja laadunvarmistus

Projektissa on noudatettu hyviä ohjelmointitapoja ja käytetty seuraavia työkaluja:

- **ESLint** – staattinen koodinanalyysi
- **Prettier** – automaattinen muotoilu
- **EditorConfig** – standardoidut editoriasetukset

---

## Käyttö

Avaa juurikansion **`index.html`** selaimessa. Sivu toimii keskitettynä valikkona, josta pääset siirtymään kaikkiin kurssin harjoituksiin.
