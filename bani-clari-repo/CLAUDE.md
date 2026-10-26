# Bani Clari

Aplicație de educație financiară pentru România, în stil Duolingo: lecții de câteva minute, 7 niveluri, unelte practice și un plan personal de bani pentru fiecare utilizator. Fondatori: Andrei Florea (tehnic) și Gabriel Ionuț Cîrstea (produs și business), parteneri egali.

## Pentru Claude, la fiecare sesiune
1. Folosește skill-ul `bani-clari` din `.claude/skills/` (contextul complet al proiectului și regulile).
2. Citește `docs/PROGRESS.md` și `docs/DECISIONS.md` înainte de orice. Ce scrie acolo are prioritate.
3. Lucrează pe un branch propriu (`andrei/...` sau `gabriel/...`), niciodată direct pe `main`.
4. La final rulează `/handoff`.

## Reguli scurte
- Educație, nu consultanță: nicio recomandare de produse, bănci sau investiții.
- GDPR: date minime; sub 16 ani, acordul părinților.
- Fără cifre inventate; calculele ilustrative se marchează ca atare.
- Fără secrete în Git: cheile stau în `.env` (ignorat) și în Supabase Edge Functions.
- Textele pentru utilizatori: română cu diacritice corecte.

## Structura
- `docs/` progres, decizii, documente de lucru
- `content/lectii/` lecțiile, câte un fișier Markdown pe lecție
- codul aplicației se adaugă după ce stack-ul e confirmat în `docs/DECISIONS.md`
