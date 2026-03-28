## Hi there 👋
# zG Era — Zubeen da's Legacy Movement
### *Unity for Golden Assam*

> *"জুবিন যুগৰ নৱপ্ৰজন্ম হৈ দাদাৰ সোণৰ অসমৰ সপোন পূৰ্ণ কৰাৰ হকে, আমি আমাৰ দায়িত্ব আৰু কৰ্তব্য নিষ্ঠাৰে পালন কৰি আগুৱাই যোৱাৰ প্ৰচেষ্টা।"*

---

## What is zG Era?

**zG Era** is a grassroots cultural movement born in Assam, dedicated to preserving and carrying forward the legacy of legendary musician and cultural icon **Zubeen Garg (Zubeen da)**. This is not a fan page. This is a movement — built on unity, socialist ideology, and the collective dream of a Golden Assam.

The name carries a triple meaning:
- **Zubeen Garg's Era** — honouring the man and his music
- **Zubeen's Golden Era** — the golden age he represented
- **Zubeen's Generational Era** — passing the torch to the next generation

---

## The Three Pillars

| Pillar | Vision |
|--------|--------|
| 🏛️ **Legacy Preservation** | Document, share, and honour Zubeen da's music, ideology, and life |
| 🤝 **Community for Unity** | Build real human connections — physical gatherings, shared purpose |
| 🌱 **Socialist Path** | Create opportunities together; what one cannot do alone, we do united |

---

## This Repository

This repo contains the **official production website** of the zG Era movement — a bilingual (English / Assamese) landing page and waitlist built to gather the first wave of Comrades.

### Features

- Bilingual UI — English & Assamese toggle
- Waitlist form connected to **Google Sheets** via Apps Script
- Real submission counter (starts at 0, increments on every verified join)
- Custom animated district picker — all 35 districts of Assam + Indian / Out of Country
- Scroll-reveal animations, typewriter hero, gamosa-inspired design language
- Fully responsive — mobile first
- No frameworks — plain HTML, Tailwind CSS (CDN), vanilla JS

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 |
| Styling | Tailwind CSS (CDN) |
| Fonts | Space Grotesk, Cinzel, Cormorant Garamond, Noto Sans Bengali |
| Form Backend | Google Apps Script → Google Sheets |
| Hosting | *(deploy to Vercel / Netlify / GitHub Pages)* |
| Language | Vanilla JavaScript |

---

## Project Structure

```
zG-Era/
├── index.html          # Main production webpage (single file)
├── README.md           # This file
└── assets/             # (optional) local images, PDFs, banner files
```

---

## Google Sheets Integration

Form submissions go directly to a Google Sheet via Apps Script.

The Apps Script endpoint accepts the following fields via POST:

| Field | Description |
|-------|-------------|
| `Name` | Full name of the Comrade |
| `Email` | Email address |
| `WhatsApp` | 10-digit WhatsApp number |
| `District` | Selected from Assam district list or Indian / Out of Country |
| `Meaning` | What Zubeen da means to them |
| `Source` | Always `zG-Era-Website-Waitlist` |
| `Timestamp` | ISO 8601 timestamp of submission |

To update the endpoint, change `GOOGLE_SCRIPT_URL` at the top of the `<script>` block in `index.html`.

---

## Roadmap

```
Phase 1 — NOW (Ongoing)
  ✅ Website live with waitlist
  ✅ Google Sheets data collection
  ✅ Physical letter distribution at Zubeen Khetra, Sonapur
  ✅ WhatsApp Community launched

Phase 2 — At 100 Members
  ⬜ First physical gathering at Zubeen Khetra
  ⬜ Speeches, collective pledge, role assignments

Phase 3 — Platform Launch
  ⬜ Full zG Era digital platform
  ⬜ Tree plantation tracking
  ⬜ ZG Coins (community reward system)
  ⬜ Cultural collaboration tools

Phase 4 — The Dream
  ⬜ Permanent open stage at Zubeen Khetra
  ⬜ Permanent monument to Zubeen da's golden legacy
```

---

## Getting Started (Local Development)

No build tools required. Just open the file.

```bash
git clone https://github.com/YOUR_USERNAME/zG-Era.git
cd zG-Era
# Open index.html in your browser
open index.html
```

For live reload during development, use VS Code's Live Server extension or any static server:

```bash
npx serve .
```

---

## Contributing

This movement belongs to all of Assam. If you want to contribute — code, design, content, or translation — open an issue or a pull request. All contributions are welcome.

Before contributing, please keep these values in mind:
- Unity over division
- Substance over noise
- Legacy over ego

---

## Community

| Platform | Link |
|----------|------|
| 💬 WhatsApp Community | [Join here](https://chat.whatsapp.com/Icg9yPkvPagAoWxJiJ67ZU) |
| 🌐 Website | Join https://zg-era.github.io/ZG-Era/

---

## License

This project is open source and free to use for non-commercial, cultural, and community purposes aligned with the values of the zG Era movement.

---

  জয় আই অসম। জয় জুবিন দা। 🙏
  Built by the youth of Assam, for the future of Assam.
-->
