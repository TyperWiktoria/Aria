# ARIA APG — Formularz demonstracyjny

Formularz rejestracji na szkolenie UX implementujący wzorce dostępności
zgodne z WAI-ARIA Authoring Practices Guide (W3C).

## Zawartość

- '[https://github.com/TyperWiktoria/Aria/blob/0d661b5b74dfdeceb9494dc35d5c778d74ddd497/aria-formularz.html]' — działający formularz z pełną implementacją ARIA APG
- `aria-raport.txt` — raport z analizy implementacji

## Zastosowane wzorce ARIA APG

| Wzorzec | Elementy |
|---|---|
| Landmark Regions | `role="banner/main/navigation/contentinfo"` |
| Dialog (Modal) | focus trap, Escape, powrót fokusa do triggera |
| Alert | `role="alert"` na błędach inline i globalnym banerze |
| Tooltip | `role="tooltip"` + widoczny na hover i fokusie klawiatury |
| Radio Group | `fieldset/legend` + `role="radiogroup"` |
| Live Regions | `aria-live="polite/assertive"` na statusach i liczniku znaków |

## Kluczowe atrybuty

- `aria-required`, `aria-invalid`, `aria-describedby` — walidacja pól
- `aria-modal="true"`, `aria-labelledby` — dialog
- `aria-current="page/step"` — nawigacja i wskaźnik kroków
- `aria-busy="true"` — stan ładowania prz
