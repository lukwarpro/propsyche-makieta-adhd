# Makieta: diagnoza integracji sensorycznej

Wizualna propozycja Grok (31 sierpnia 2026) dla **nowej** podstrony
`/diagnoza-integracji-sensorycznej-bydgoszcz`.

To **nie jest produkcja**. Strony jeszcze nie ma na żywo.

Język wizualny: **karta badania** — ten sam co makieta ADHD dorosłych
w tym PR (`index.html`), nie tealowy landing KORP.

## Podgląd

- [Makieta HTML](./si.html)
- [htmlpreview](https://htmlpreview.github.io/?https://github.com/lukwarpro/propsyche-makieta-adhd/blob/grok/adhd-dorosli-karta-badania/si.html)
- Handoff produkcyjny: [zadanie Coding w Notion](https://app.notion.com/p/3cdc72a6aff38101a541e3a5d6cb26f8)

## Brief

- H1: Diagnoza integracji sensorycznej (bez „Bydgoszcz”)
- Eyebrow: Test diagnostyczny
- CTA: **Zadzwoń do rejestracji** (nie „Zrób pierwszy krok” — blacklist CMS)
- Dwie ścieżki: 2–11 lat = **850 zł**, od 12. lat = **800 zł**
- Opinia **150 zł w kwocie**, nie „na życzenie”
- Testy kalifornijskie: pełne normy głównie od ok. 4;0 — poniżej wywiad + obserwacja
- Próba Schildera (test wyprostowanych rąk) + praksja na ścieżce 12+
- Tylko certyfikowany terapeuta SI (PSTIS); nazwiska nie podajemy
- Bez cennika terapii SI, bez recenzji Google, bez koralowego callbara

## Cennik (źródło: brief Łukasza)

| Ścieżka 2–11 | zł | Ścieżka 12+ | zł |
| --- | --- | --- | --- |
| Wywiad + kwestionariusz | 150 | Wywiad + kwestionariusz | 150 |
| Obserwacja kliniczna 50 min | 200 | Rozmowa + Schilder + praksja 1,5 h | 350 |
| Testy kalifornijskie 50 min | 200 | Omówienie | 150 |
| Omówienie | 150 | Opinia | 150 |
| Opinia | 150 | **Razem** | **800** |
| **Razem** | **850** | | |

Nie reuse’ować `diag-dziecko-opinia-psychologiczna` (300 zł). Osobne id w `pricing.ts`.

## Po akceptacji wizualnej

Port CSS + markup do `_new_astro` w `lukwarpro/pro-psyche.pl`:

1. `src/pages/diagnoza-integracji-sensorycznej-bydgoszcz.astro`
2. `src/data/si/body.html` + `faq.ts`
3. `pricing.ts` — **dopiero po zwolnieniu claimu KORP** (grok-korp-20260831)
4. Header: pozycja „Integracja sensoryczna” w dropdownie „Diagnoza dzieci i młodzieży”
5. `public/data/services.json`

Do tego czasu `noindex`. Zdjęcia produkcyjne: istniejące z diagnozy psychologicznej / ADHD dzieci, nie wygenerowane wnętrza.
