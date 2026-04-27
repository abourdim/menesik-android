# Play Store listing — Menesik (مناسك)

Draft copy for Google Play Console "Main store listing" page. Play Console accepts separate translations per language — upload all three.

---

## Metadata (common to all languages)

- **Package name**: `org.workshopdiy.menesik`
- **Category**: `Books & Reference` (primary), `Education` (secondary if allowed)
- **Tags**: Islamic studies, Arabic, trilingual, education, al-Ghazali
- **Contact email**: `abdelhak.bourdim@gmail.com`
- **Website**: `https://workshop-diy.org`
- **Privacy policy URL**: REQUIRED — host a simple page (see template at end of this file).
- **Content rating**: Everyone (no violence, no gambling, no mature content).
- **Ads**: No.
- **In-app purchases**: No.
- **Data safety**: No data collected, no data shared.

---

## Arabic (ar) — primary

### App name (≤30 chars)
```
مناسك
```

### Short description (≤80 chars)
```
دليل شامل متعدد اللغات لمناسك الحج والعمرة — بدون اتصال
```

### Full description (≤4000 chars)
```
🕌 مناسك

دليل شامل متعدد اللغات لمناسك الحج والعمرة (عربي/فرنسي/إنجليزي). يشمل المناسك خطوة بخطوة، قائمة مراجعة تفاعلية مع تتبع التقدم، ومجموعة منتقاة من الأدعية. يعمل بدون اتصال بالإنترنت تمامًا.

— من workshop-diy.org
```

---

## English (en)

### App name
```
Menesik — Menesik
```

### Short description
```
Multilingual Hajj & Umrah pilgrim guide — offline, AR/FR/EN
```

### Full description
```
🕌 Menesik

Complete Hajj & Umrah pilgrim guide in three languages (AR/FR/EN). Includes step-by-step rituals, an interactive checklist with progress tracking, and a curated dua collection. Fully offline-capable — essential when there is no signal in Mecca.

— From workshop-diy.org
```

---

## French (fr)

### App name
```
Menesik — Menesik
```

### Short description
```
Guide multilingue du Hajj et de la Omra — hors ligne, AR/FR/EN
```

### Full description
```
🕌 Menesik

Guide multilingue complet du Hajj et de la Omra (AR/FR/EN). Inclut les rites étape par étape, une checklist interactive avec suivi de progression, et une collection de duas. Entièrement hors ligne — essentiel quand il n'y a pas de réseau à La Mecque.

— De workshop-diy.org
```

---

## Graphics needed (minimum)

| Asset | Size | Source |
|---|---|---|
| App icon | 512×512 PNG | `store-assets/play-store-icon-512.png` (regenerate per book) |
| Feature graphic | 1024×500 PNG | `store-assets/feature-graphic.png` (render from `feature-graphic.html`) |
| Phone screenshots | min 2, 320–3840px, 16:9 portrait | Capture from emulator / real device |
| 7" tablet screenshots (optional) | min 2, 1024×600+ | Run emulator with tablet profile |

Screenshots to capture (book-specific — adjust list to actual app screens):
1. Home / cover / introduction
2. Main content navigation
3. Reading or interaction mode
4. Quiz or self-assessment (if applicable)
5. Theme switch (optional — shows the 3 variants)

---

## Privacy policy template

Copy to a public page (GitHub Pages works). Change email + date.

```
Privacy Policy — Menesik
Last updated: 2026-04-27

The Menesik app does not collect, store, transmit, or share any personal
data. All content is bundled with the app and runs entirely on your device.
The app does not use analytics, advertising networks, crash reporters, or
third-party SDKs.

The app requires no special permissions beyond internet access, which is
used only to load the occasional external link (e.g. workshop-diy.org) if
you tap it — never silently in the background.

If you have questions, contact: abdelhak.bourdim@gmail.com
```
