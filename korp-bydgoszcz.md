# Makieta: KORP Bydgoszcz

Wizualna propozycja Grok (31 sierpnia 2026) dla nowej podstrony
[/korp-bydgoszcz](https://pro-psyche.pl/korp-bydgoszcz) — Karty Oceny Rozwoju Psychoruchowego.

To **nie jest produkcja**. Strony jeszcze nie ma na żywo.

## Podgląd

- [Makieta HTML](./korp-bydgoszcz.html)
- [htmlpreview](https://htmlpreview.github.io/?https://github.com/lukwarpro/propsyche-makieta-adhd/blob/grok/adhd-dorosli-karta-badania/korp-bydgoszcz.html)
- Źródło Astro do wrzucenia do `pro-psyche.pl`: [korp-bydgoszcz.astro](./korp-bydgoszcz.astro)

## Brief

- element procesu diagnostycznego, nie werdykt
- 1 m.ż.–9 r.ż., 7 sfer, 13 grup wiekowych, polskie normy
- wywiad z rodzicem + badanie dziecka (1–2 spotkania)
- pakiet ok. 2 h = **400 zł**
- opinia pisemna **300 zł osobno** (jak ADOS-2 / ADI-R / SB5) — do potwierdzenia

## Szablon

`DiagnosticTestPage` jak `/ids-2-bydgoszcz`. Głos: ADOS-2 / ADI-R / redesign ADHD
(papier kremowy, Fraunces, teal).

## Przed merge do `pro-psyche.pl`

1. Skopiować `korp-bydgoszcz.astro` → `_new_astro/src/pages/korp-bydgoszcz.astro`
2. `pricing.ts`: id `diag-dziecko-korp`, 400 zł, dopisać KORP do subtitle kategorii
3. `public/data/services.json`
4. Linki krzyżowe na ADOS-2 / ADI-R / IDS-2 / SB5
