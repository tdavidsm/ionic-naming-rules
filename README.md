# 🧭 Ionic Naming Rules: Which Rule Applies?

A practice activity that teaches students **how to decide** which naming rule an ionic compound uses: the basic rule, Roman numerals, polyatomic ions, or Roman numerals **and** polyatomic ions.

**▶ Open it:** https://tdavidsm.github.io/ionic-naming-rules/

## The idea: two yes/no questions
1. **Can the metal have more than one charge?** (In a name: is there a Roman numeral?)
2. **Is there a polyatomic ion?** (In a formula: a group of atoms like NO₃ or OH, or NH₄ at the front. In a name: -ate/-ite, hydroxide, or ammonium.)

| | No polyatomic ion | Polyatomic ion |
|---|---|---|
| **One-charge metal** | **Basic ionic**: NaCl, sodium chloride | **Polyatomic**: Ca(NO₃)₂, calcium nitrate |
| **Multi-charge metal** | **Roman numeral**: FeCl₃, iron(III) chloride | **Roman numeral + polyatomic**: Fe(NO₃)₃, iron(III) nitrate |

## Tabs
| Tab | What students do |
|---|---|
| **How to Decide** | An animated 2×2 decision matrix, clue lists for formulas and names, the eight polyatomic ions used, and a quick check (answer both questions for 4 compounds) |
| **Names → formulas** (3 tabs) | *Basic vs. Roman numeral*, *Basic vs. polyatomic*, *Roman vs. polyatomic*. A side-by-side animated lesson of look-alike names, then 4 practice problems |
| **Formulas → names** (3 tabs) | The same three comparisons, starting from formulas |
| **Mixed Challenge** | All four rules, both directions, 8 problems |

Each lesson animation compares similar-looking compounds (for example **NaCl / FeCl₃**, **sodium nitride / sodium nitrate**, **Zn₃P₂ / Zn₃(PO₄)₂**, **NH₄Cl / NaCl**, or a four-way grid built from the same pieces). It asks the two questions, shows the verdict, then builds the answer step by step, with the parts that supply each piece of the answer highlighted and flying into place.

### Practice problems
- Problems come in **matched pairs** that differ in exactly one thing. After the second one, a **Compare the pair** box shows both side by side and explains the difference.
- For every problem the student first answers the **two yes/no questions**. A wrong answer highlights the clue in the compound and explains it. Then they **type the name or formula**.
- Typed answers get specific hints (symbol instead of name, missing or extra Roman numeral, a digit instead of a numeral, -ide on a polyatomic ion, missing parentheses, wrong subscripts, wrong order). **Show me how** plays the explanation animation for that exact compound, and it opens automatically after three misses.
- Wrong answers never reset anything. Progress is saved on the device.

## Chemistry covered
- One-charge metals: Li, Na, K, Mg, Ca, Ba, Al, Zn, Ag.
- Multi-charge metals: Fe, Cu, Sn, Pb, Cr, Co (two common charges each).
- Single-atom negative ions: Cl, Br, F, I, O, S, N, P.
- Polyatomic ions: NH₄⁺, OH⁻, NO₃⁻, SO₄²⁻, CO₃²⁻, PO₄³⁻, ClO₃⁻, C₂H₃O₂⁻. Parentheses appear only when more than one polyatomic ion is needed. Spellings like aluminium and sulphide are accepted.

## Teacher notes
- Tabs unlock in order. Add `#unlock` to the URL (`.../ionic-naming-rules/#unlock`) to open them all for demonstration.
- Finishing every section gives a **completion code** (initials in two of its slots). To add the **Turn it in** button that opens your Google Form pre-filled, paste the form's `viewform` link into `FORM_BASE` near the end of `index.html` (and check `FORM_ENTRY` holds the Name and Code entry IDs).

## Tech
Single self-contained `index.html`: plain HTML/CSS/JS, no dependencies, touch-friendly for iPad, with the same always-visible scroll strip as the other tools. Deployed via GitHub Pages from `main`.
