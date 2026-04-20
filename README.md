# MycountryGuide

**Bilingual DE/EN market intelligence platform powered by World Bank data and AI analysis**

[Live Platform →](https://mycountryguide.de)

---

## The Problem

Business professionals entering new markets — especially German companies looking at Africa or emerging economies — face scattered, outdated, or inaccessible market intelligence. World Bank data exists but it's not designed for quick business decisions. AI summaries exist but they lack real data behind them.

MycountryGuide combines both: real economic data with AI-generated business context, in both German and English.

---

## What MycountryGuide Does

- Select any country via interactive world map
- View live economic indicators (GDP, trade volume, demographics, exchange rates)
- Read AI-generated market intelligence summaries contextualized for business use
- Compare two markets side by side
- Access global rankings across key economic indicators
- Switch seamlessly between German and English throughout

---

## How the AI Works

Raw World Bank data tells you a country's GDP. It doesn't tell you what that means for a German SME considering entry.

MycountryGuide uses **Claude API** and **Google Generative AI** to bridge that gap:

1. Live economic data is fetched from World Bank and REST Countries APIs
2. The data is structured and passed to the AI with a business intelligence framing
3. The AI generates context — market maturity, risk factors, trade relationship notes — anchored to the real numbers
4. Output is translated and localized for both DE and EN audiences

The result is market intelligence that reads like an analyst wrote it, backed by live data.

---

## Built With

- **Next.js** + TypeScript — framework
- **Anthropic Claude API** + Google Generative AI — market analysis
- **World Bank API** + REST Countries API — live economic data
- **Mapbox GL** — interactive country selection
- **Fuse.js** — fuzzy search
- **Tailwind CSS** — UI (dark/light themes)
- **Vercel** — deployment

---

**Creator:** Yoseph Aberha · [mycountryguide.de](https://mycountryguide.de) · [LinkedIn](https://linkedin.com/in/yoseph-aberha)
