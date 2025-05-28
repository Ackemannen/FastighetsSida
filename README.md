# FastighetsSida

En modern React-applikation för att visa och hantera lägenhetslistor. Projektet är byggt med React och använder React Router för navigering mellan olika sidor.

## Funktioner

- **Startsida** med översikt och navigation
- **Lägenhetslista** där användaren kan se alla lediga lägenheter
- **Detaljsida för lägenhet** med mer information om vald lägenhet
- **Responsiv navbar** med sidomeny och sociala medier-länkar

## Projektstruktur

```
src/
  components/
    Navbar/
      Navbar.jsx
      Navbar.css
  pages/
    home/
      Home.jsx
    apartment/
      Apartment.jsx
    apartments-list/
      ApartmentsList.jsx
  apartments.js
  App.js
  ScrollToTop.js
```

## Routing

- `/` – Startsida
- `/apartmentlistings` – Lista över alla lägenheter
- `/apartment` – Detaljsida för vald lägenhet
