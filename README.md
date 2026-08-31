# Makiety: karta badania (Propsyche)

Wizualna propozycja Grok (sierpień 2026). To **nie jest produkcja**.
Język: karta badania / protokół diagnostyczny zamiast landingu SaaS.

Papier kremowy `#f2ece2`, atrament granatowy `#1d3557`, jeden teal `#0c656c`.
Fraunces + IBM Plex Sans. Sticky spis. Callbar granatowy, tylko mobile.
Bez blobów, glass, hover-lift, count-up, koralowego callbara.

## Podgląd

### ADHD u dorosłych (redesign istniejącego URL)

- [Makieta HTML](./index.html) · [htmlpreview](https://htmlpreview.github.io/?https://github.com/lukwarpro/propsyche-makieta-adhd/blob/grok/adhd-dorosli-karta-badania/index.html)
- Kopia robocza: [adhd-dorosli-complete-v3.html](./adhd-dorosli-complete-v3.html)
- Żywa strona: <https://pro-psyche.pl/leczenie-i-diagnoza-adhd-u-doroslych>
- URL produkcji **bez zmian** (~315k wyświetleń/rok)

### Diagnoza integracji sensorycznej (nowa strona)

- [Makieta HTML](./si.html) · [htmlpreview](https://htmlpreview.github.io/?https://github.com/lukwarpro/propsyche-makieta-adhd/blob/grok/adhd-dorosli-karta-badania/si.html)
- Notatka: [si.md](./si.md)
- Docelowy URL: `/diagnoza-integracji-sensorycznej-bydgoszcz` (strony jeszcze nie ma)
- Handoff: [zadanie Coding](https://app.notion.com/p/3cdc72a6aff38101a541e3a5d6cb26f8)

CTA: „Zadzwoń do rejestracji”. Dwie ścieżki: 850 zł (2–11) / 800 zł (12+).
Opinia w cenie. Bez nazwiska terapeuty, bez recenzji Google, bez cennika terapii.

### KORP Bydgoszcz (inna sesja)

- [korp-bydgoszcz.html](./korp-bydgoszcz.html) — **inny język** (tealowy landing jak żywe ADHD, nie karta badania)
- Notatka: [korp-bydgoszcz.md](./korp-bydgoszcz.md)

## Po akceptacji wizualnej

Port CSS i markup do `_new_astro` w `lukwarpro/pro-psyche.pl`.
ADHD: bez zmiany URL. SI: nowa strona. `noindex` na makietach zostaje
aż do recenzji medycznej.
