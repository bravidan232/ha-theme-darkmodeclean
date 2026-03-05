# DarkModeClean Themes for Home Assistant  
Premium blåtema för Home Assistant med stöd för mörkt läge och MD3-design.

Detta repository innehåller **två teman**:

- **DarkModeClean** – standardversionen med ren layout  
- **DarkModeClean-Pro** – premium “glassmorphism”-version med blur, glow och djupkänsla  

Båda är optimerade för **Home Assistant 2025–2026** med det nya Material Design 3-gränssnittet.

---

## 🖼️ Funktioner
✔ Fullt stöd för HA mörkt läge (MD3)  
✔ Blue Surface / Deep Blue Container färgprofil  
✔ Anpassade kort och dialoger (card-mod-stöd)  
✔ Bakgrundsbild för dashboards  
✔ Sidebar och header i enhetlig blå ton  
✔ Full HACS-kompatibilitet för enkel installation  
✔ Pro-version: transparenta kort, blur, soft shadows, glas-effekt  

---

## 📦 Mappstruktur

Repositoryt följer HACS tema-specifikationen:
ha-theme-darkmodeclean/
│
├── DarkModeClean/
│   ├── theme/
│   │   └── darkmodeclean.yaml
│   └── www/
│       └── HABG_dark.png
│
└── DarkModeClean-Pro/
├── theme/
│   └── darkmodeclean-pro.yaml
└── www/
└── HABG_dark.png

---

## 🔧 Installation via HACS (Rekommenderas)

### 1. Installera HACS
Följ den officiella guiden på HACS hemsida eller via terminal:

```bash
wget -O - https://get.hacs.xyz | bash -

Starta om Home Assistant efter installation.

✨ Tack
Detta tema är skapat för interna Home Assistant-projekt, men repositoryt är publikt så HACS kan läsa det.
Det går utmärkt att använda privat – ingen hittar det utan att veta den exakta URL:en.
