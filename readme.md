> ⚠️ **WAARSCHUWING: TEST VERSIE**
> Deze gecombineerde **Porsche & Nissan Dossier Manager** is een **TEST VERSIE**.
> 
> **IMPORT / EXPORT WAARSCHUWING:**
> De CSV import- en exportfuncties van deze testversie zijn **NIET COMPATIBEL** met de losse, eerdere versies van de Porsche en Nissan apps. Importeer geen CSV-bestanden uit oudere applicaties om datacorruptie of verlies van velden te voorkomen.

---

## 📌 Over deze applicatie

Dit is een gecombineerde webapplicatie (single-file HTML) voor het beheren en verwerken van pechhulp-dossiers voor zowel **Porsche Assistance** als **Nissan Assistance**. Via de merkschakelaar bovenaan kan eenvoudig gewisseld worden tussen de twee merken.

### ✨ Belangrijkste functionaliteiten

- **Snel wisselen tussen merken**: Schakel via het menu direct tussen Porsche en Nissan. Het thema (paars/rood accent vs. blauw accent) en de merk-specifieke velden passen zich automatisch aan.
- **Merk-specifieke formulieren**:
  - **Porsche**: Inclusief modelselectie (911, Taycan, etc.) en Porsche Centrum vestigingen.
  - **Nissan**: Inclusief modelselectie (Micra, Qashqai, Ariya, etc.) en Nissan Dealer gegevens.
- **Geïntegreerd dossierbeheer**:
  - Aanmaken, bewerken, kopiëren en verwijderen van dossiers.
  - Lokale opslag (`localStorage`) per merk (`p_dossiers` en `n_dossiers`).
  - Zoekfunctie op dossiernummer, klantnaam of kenteken.
- **Handige tools**:
  - Directe koppelingen naar **Google Maps**, **Google Zoeken** en **RDW Kentekencheck**.
  - Snel kopiëren van gestructureerde dossiertekst naar het klembord.
- **Toegankelijkheid & Thema's**:
  - 3 thema-modi: Licht, Middel en Donker (geoptimaliseerd voor hoog contrast en leesbaarheid).
  - Aanpasbare lettergrootte.

---

## 🚀 Installatie & Gebruik

De applicatie kan op twee manieren worden gebruikt:

### 1. Direct gebruiken via de computer (Offline / Lokaal)
1. Download het bestand `index.html`.
2. Sla het op een gewenste locatie op je PC op.
3. Dubbelklik op het bestand om het direct te openen in een browser (Chrome, Edge, Safari, Firefox). 
   *Er is geen internetverbinding of webserver nodig.*

### 2. Installeren als Progressive Web App (PWA)
Als de pagina wordt gehost via GitHub Pages (of een HTTPS-verbinding):
- **Desktop (Chrome/Edge)**: Klik op het installatie-icoon aan de rechterkant van de adresbalk (of ga naar het menu `...` > *App installeren*) om de applicatie als een losse desktop-app te installeren.
- **Mobiel / Tablet (iOS/Android)**: 
  - **Safari (iOS)**: Tik op de *Delen*-knop en kies **'Zet op begintestcherm'**.
  - **Chrome (Android)**: Tik op het menu met drie puntjes en kies **'Toevoegen aan startscherm'** of **'App installeren'**.

---

## 📋 Technische details

- **Bestandstype**: Single-file HTML (`index.html`) met vanilla JavaScript en ingebouwde CSS.
- **Data-opslag**: In-browser via `localStorage`.
- **Import/Export**: Ondersteuning voor CSV-export en CSV-import (alleen compatibel binnen deze specifieke testversie).

---

*Gecompileerd voor intern gebruik.*