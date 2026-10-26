---
description: Închide sesiunea: actualizează progresul, salvează pe GitHub și deschide un PR.
---
Închide sesiunea de lucru pe Bani Clari:
1. Rulează `git status` și rezumă ce s-a schimbat.
2. Adaugă sus în `docs/PROGRESS.md` o intrare: data de azi, cine a lucrat (din numele branch-ului sau întreabă), ce s-a făcut, ce urmează, ce e blocat.
3. Dacă s-a luat o decizie confirmată de amândoi fondatorii, adaug-o în `docs/DECISIONS.md`. Dacă e doar o propunere, trece-o la „De decis”.
4. Verifică să nu existe chei, parole sau `.env` în modificări.
5. Fă commit cu un mesaj clar în română, `git push`, apoi deschide un PR spre `main` cu `gh pr create`, cu rezumatul și ce trebuie verificat.
6. Nu face merge. Spune-mi linkul PR-ului și ce ar trebui să verifice celălalt fondator.
