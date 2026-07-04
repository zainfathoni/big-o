# Big-O Resources

## Knowledge

- [Slides: _Kompleksitas Algoritma (Big-O)_ — Zain Fathoni, Politeknik Negeri Jember, 26 Sep 2020](https://zainf.dev/big-o)
  The canonical source for this workspace (local copy: `assets/big-o-2020-jember-slides.pdf`). Use for: the courier/TSP motivation, T(n) step-counting examples, best/worst/average case, and the Θ/O/Ω definitions. In Indonesian.
  ⚠️ Erratum, slide 34 (Big-Ω): the text says T(f(n)) is "selalu **lebih kecil** daripada k ⋅ f(n)" — for a lower bound it should be "lebih **besar**". The accompanying framing ("Big-Ω adalah batas bawah Big-Θ") is correct.
- [Khan Academy — Asymptotic notation](https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/asymptotic-notation)
  The source the 2020 deck itself leans on for Θ/O/Ω. Use for: precise but accessible definitions, and the "why Big-O is the useful upper bound" argument.
- [Big-O Cheat Sheet](https://www.bigocheatsheet.com)
  The growth-curve chart and data-structure/sort tables the deck translates. Use for: the visual ladder of growth functions and quick complexity lookups.
- [Brilliant — Traveling Salesperson Problem](https://brilliant.org/wiki/traveling-salesperson-problem/)
  Source of the courier map illustration. Use for: the brute-force vs greedy walkthrough and the (n−1)! route-count explosion.
- [Rinaldi Munir (ITB) — Kompleksitas Algoritma](https://informatika.stei.itb.ac.id/~rinaldi.munir/Matdis/2008-2009/Kompleksitas%20Algoritma.ppt)
  The academic lineage of the 2020 deck. Use for: additional worked T(n) examples in Indonesian.

## Wisdom (Communities)

- [Pejuang Kode Discord](https://zainf.dev/discord)
  Zain's own community. Use for: follow-up questions after the BUILD Camp session, in Indonesian.
- Live: the BUILD Camp room itself, 4 July 2026.
  Use for: quiz answers, topic votes, and wrong-answer steering during the session.

## Gaps

- No hands-on *measurement* resource yet (e.g. a script that times an O(n) vs O(n²) function as n grows) — a live-session candidate if the room wants empirical proof.
