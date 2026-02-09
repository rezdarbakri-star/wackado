# ⚡ Puls

**Håll koll på allt. Varje dag.**

En progressiv webbapp (PWA) för att spåra och hantera alla återkommande uppgifter i ditt liv – från content-publicering till städning, träning och semester.

## Funktioner

- 📊 **Kategorivy** – Varje livsområde har en egen progress bar som visar urgency
- ✅ **One-tap check** – Tryck ✓ för att markera en uppgift som gjord
- 📅 **Manuellt datum** – Logga en dag du glömde med datumväljaren
- 🏖️ **Semester-nedräkning** – Ditt ljus i tunneln, alltid synligt högst upp
- 🌓 **Tema-toggle** – Mörkt läge + ljust pastelltema
- 📱 **Mobile-first** – Designad för mobilen, fungerar överallt
- 💾 **Offline-stöd** – PWA med service worker

## Kom igång

### GitHub Pages

1. Skapa ett nytt GitHub-repo
2. Ladda upp alla filer (`index.html`, `manifest.json`, `sw.js`)
3. Gå till **Settings → Pages → Source: main branch**
4. Din app finns nu på `https://dittnamn.github.io/reponamn/`

### Installera som app

Öppna sidan i Chrome/Safari på mobilen → "Lägg till på hemskärmen"

## Filstruktur

```
puls-pwa/
├── index.html      ← Hela appen (HTML + CSS + JS)
├── manifest.json   ← PWA-manifest
├── sw.js           ← Service worker (offline-stöd)
└── README.md
```

## Nästa steg

- [ ] Google-inloggning
- [ ] Google Calendar-synk med notiser
- [ ] Molnsynk av data
