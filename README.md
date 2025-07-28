⚠️ Toto je osobní studijní projekt. Není určen pro produkční použití.  
README je psané v češtině, protože projekt je součástí mého studijního archivu.

# 🗺️ LnL Legends

**LnL Legends** je interaktivní mapová hra postavená v čistém JavaScriptu. Hráč dostane obrázek určitého místa a musí na mapě označit, kde se toto místo nachází. Na základě přesnosti a rychlosti odpovědi získává skóre.

🌐 [Live demo](https://tomasulman-lnl-legends.netlify.app/)

---

## 🕹️ Herní princip

- Vyber si kvíz z úvodní nabídky a klikni na **Play**.
- Tipni polohu místa zobrazeného na fotce kliknutím do mapy.
- Po potvrzení tipu se zobrazí:
  - Správná pozice
  - Čára mezi tvým tipem a skutečným místem
  - Vzdálenost v km + skóre
- Kvíz pokračuje další otázkou.
- Po dokončení následuje shrnutí celkového skóre.

---

## 📚 Funkce

- Více než 60 otázek rozdělených do tematických kvízů (Evropa, svět, památky, ČR)
- Více úrovní obtížnosti
- Animované zobrazení výsledků
- Reakce na přesnost a rychlost (počítání skóre podle vzdálenosti a času)
- Lokální ukládání skóre do `localStorage`
- Stylová UI s responzivním designem a vlastními kurzory

---

## 🛠️ Technologie

- 🧠 **JavaScript (OOP)** – hlavní logika hry pomocí tříd (`App`, `Quiz`, `Question`)
- 🧭 **Leaflet.js** – interaktivní mapy
- 🗺️ **OpenStreetMap** & **CartoDB** – mapové podklady
- 🖼️ **Pixabay** – obrázky míst
- 🎨 **HTML & CSS** – vlastní responzivní stylování, přizpůsobeno i pro mobilní zařízení

---

## 🧩 Struktura projektu

| Soubor            | Popis |
|-------------------|-------|
| `index.html`      | Výchozí HTML soubor pro spuštění |
| `style.css`       | Vlastní stylování, včetně mobilních přizpůsobení |
| `app.js`          | Hlavní třída aplikace (UI, přepínání stavů, spuštění kvízu) |
| `quiz.js`         | Herní logika – vykreslování mapy, výpočet skóre, animace |
| `question.js`     | Jednoduchá třída pro uchování informací o jednotlivých otázkách |
| `quizData.js`     | Definice všech kvízů, včetně otázek, stylů map, časovačů apod. |
| `Images/`         | Obrázky pro kvízy, ikony, kurzory a další assety |
| `Architecture.jpg`| Náhled architektury hry (součást dokumentace) |

---

## 🚀 Lokální spuštění

```bash
git clone https://github.com/TomasUlman/LnL_Legends.git
cd LnL_Legends
# spusť přímo v prohlížeči soubor index.html
```

> ⚠️ Není potřeba backend ani žádná instalace – aplikace běží čistě v prohlížeči.

---

## 📸 Screenshot
![Architektura](./Architecture.jpg)

---

## 📝 Licence & Poděkování

- Obrázky: [Pixabay](https://pixabay.com/)
- Mapy: [OpenStreetMap](https://www.openstreetmap.org/copyright), [Carto](https://carto.com/attributions)
- Mapová knihovna: [Leaflet](https://leafletjs.com/)
- Kurzory: Vlastní SVG

---

© 2025 Tomáš Ulman  
Osobní projekt pro trénink práce s Leafletem, mapovou geolokací a OOP v JavaScriptu.
