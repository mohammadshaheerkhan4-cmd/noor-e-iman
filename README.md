# Noor-e-Iman

A responsive, single-file Islamic information website.

## Publish with GitHub Pages
1. Create a public GitHub repository named `noor-e-iman`.
2. Upload `index.html` to the repository root.
3. Open Settings -> Pages.
4. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.

## Current features
- Responsive Urdu-first layout and light/dark theme
- Prayer timings by selected Pakistani city (AlAdhan API)
- Quran surah list, Arabic text and Urdu/English translation (AlQuran Cloud API)
- Hadith collection lookup (Hadith API CDN)
- Daily duas and Islamic month greeting messages
- Qibla bearing using device geolocation
- Tasbeeh counter and locally saved bookmarks
- External Islamic research links

## Important limitations
- This is a static frontend. The Islamic question search opens searches on selected external scholarly sites; it does not crawl the whole web or issue AI fatwas.
- Do not put secret API keys in this public HTML file. A secure backend is needed for any AI search integration.
- Prayer times, Hijri dates, Qibla sensor accuracy and hadith data should be checked against trusted local/primary sources.
- This site is educational and is not a substitute for a qualified scholar or mufti.
- Some features require an internet connection. API providers may change availability or terms.
