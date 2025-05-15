# Examen de Stat 2025 - USMF

Acest site conține materialele pentru pregătirea Examenului de Stat 2025 pentru Universitatea de Stat de Medicină și Farmacie "Nicolae Testemițanu".

## Utilizare cu ngrok

Pentru a evita eroarea "plugin:runtime-error-plugin", folosește versiunea compilată a site-ului:

1. Rulează site-ul în modul producție:
```bash
npm run start
```

2. Site-ul va rula pe port 5000. Poți folosi ngrok pentru a-l face accesibil:
```bash
ngrok http 5000
```

## Structura site-ului

- Site-ul are o bară laterală cu categorii medicale pe desktop
- Pe telefoane mobile, categoriile sunt afișate în centrul ecranului
- Fiecare categorie are propriile sale căsuțe cu link-uri
- Căsuțele au fundal alb, text albastru și contur colorat specific fiecărei specialități

## Tehnologii utilizate

- React + Vite
- Tailwind CSS
- Wouter pentru rutare
- Express pentru server

## Actualizare link-uri

Pentru a actualiza link-urile pentru fiecare categorie, modifică fișierul `client/src/lib/sidebar-data.ts`.