# Revision Notes: Reading Handout Standard

Wayne reviewed the first Markdown student packets and clarified the reading-handout standard.

## Correction

The current student packets are too simplified and too far removed from the original texts. They should be rebuilt as academic two-column PDF handouts produced with LaTeX.

## Revised standard

For reading handouts:

- Use the full document or coherent passage if it is short enough for a classroom handout.
- Put the source text into modern English only as much as needed for student access.
- Preserve the original author's tone, sequence, emphases, images, and intent.
- Do not replace a primary source with a broad summary or synthesized pseudo-reading.
- Include student-facing introduction and vocabulary preview.
- Keep the varied exercises at the end, fitted to the work.
- Produce academic two-column, 12pt LaTeX PDFs.
- Keep LaTeX source files in the repo alongside compiled PDFs or in a clearly named `latex/`/`pdf/` structure.

## Source length audit

### Plato, Republic Book VII, Allegory of the Cave

- The full *Republic* is far too long.
- The Cave passage, 514a–520a, is short enough for one handout.
- Recommendation: rebuild from the full cave passage in faithful modern English, not a compressed retelling.

### Francis Bacon, Novum Organum Book I, Aphorisms 38–44

- Aphorisms 38–44 are short enough for one handout, roughly 650 words in the public-domain Devey translation.
- Recommendation: use the full aphorisms 38–44 in modern English, preserving Bacon's aphoristic tone.
- Optional expansion: include later aphorisms on each idol only if Wayne wants a denser Bacon packet.

### Augustine, Confessions

- The full *Confessions* is far too long, roughly 112,000 words.
- Book I alone is several thousand words; Book II and Book VIII are also long/dense.
- Recommendation: discuss excerpt strategy. Options:
  1. Opening/restless heart from Book I.
  2. Pear theft/disordered love from Book II.
  3. Conversion/will divided against itself from Book VIII.
  4. A paired excerpt packet, clearly labeled as selected passages, not a synthetic reading.

### Frederick Douglass, Narrative of the Life of Frederick Douglass

- The full *Narrative* is too long for a single handout.
- Chapter VI is short enough, roughly 1,300 words, and directly addresses forbidden literacy.
- Chapter VII is also handout-length but longer, roughly 2,500 words, and contains the fuller account of how Douglass learned to read and the anguish knowledge brought him.
- Recommendation: use Chapter VI alone for a shorter packet, or Chapter VI + selected Chapter VII for the strongest literacy-as-liberation packet.

### John Henry Newman, The Idea of a University, Discourse V

- Full Discourse V is too long/dense for one handout, roughly 7,800 words from the Newman Reader page.
- Recommendation: discuss excerpt strategy. Best candidate sections are those defining liberal knowledge, intellectual cultivation, and the philosophical habit of mind.

## Immediate next step

Rebuild the first handout, Plato's Cave, as the model correction:

1. Use Plato, *Republic* VII, 514a–520a.
2. Modernize faithfully rather than summarize.
3. Produce `.tex` and compiled `.pdf` in two-column academic style.
4. Preserve the successful end-exercise pattern.
5. After Wayne approves the model, rebuild Bacon, then decide Augustine/Newman excerpt strategies.

## Long-work handout rule added after Plato approval

Wayne approved this working rule for longer works:

- For short works, use the full work or coherent passage in faithful modernized form.
- For novel-sized or treatise-sized works, use a relevant chapter, scene, book, or passage rather than compressing the whole work.
- If the whole work is necessary, divide it into separate handouts by chapter or coherent section.
- For a long work where students need prior context, give a brief student-facing summary of necessary front material, then include at least several pages of the real focused text.
- Avoid ``summary plus tiny excerpt'' unless there is a special reason; students should encounter a substantial passage.
- Window notes should finish with a short summary of the handout.

## Bacon rebuild

Reading 2 was rebuilt as `student-packets/02_bacon_four_idols_handout.tex` and compiled to `student-packets/02_bacon_four_idols_handout.pdf`, using Bacon's *Novum Organum* I.38–44 in faithful modernized form.

## Augustine rebuild

Reading 3 was rebuilt as `student-packets/03_augustine_divided_will_handout.tex` and compiled to `student-packets/03_augustine_divided_will_handout.pdf`. It uses the approved long-work strategy: brief front-context summary, then a focused modernized excerpt from *Confessions* Book VIII, chapters 7, 9, 11, and 12.

## Douglass rebuild

Reading 4 was rebuilt as `student-packets/04_douglass_literacy_liberation_handout.tex` and compiled to `student-packets/04_douglass_literacy_liberation_handout.pdf`. It uses a focused modernized excerpt from Douglass's *Narrative*, chapters VI–VII, centered on literacy, power, and painful awakening.

## Newman rebuild

Reading 5 was rebuilt as `student-packets/05_newman_knowledge_its_own_end_handout.tex` and compiled to `student-packets/05_newman_knowledge_its_own_end_handout.pdf`. It uses the approved long-work strategy: focused modernized passages from *The Idea of a University*, Discourse V, centered on liberal knowledge, utility, intellectual cultivation, and the philosophical habit of mind.

## Scope-and-sequence redesign: Homer inserted as Reading 2

Wayne confirmed that Homer's Sirens should work inside the revised `Do We Love Shadows?` unit. The active opening is now Plato's Cave followed by Homer, *Odyssey* Book XII, the Sirens. The teacher guide, unit brief, reading ladder, argument map, source notes, README, and final paper prompt were revised to reflect the new design. The older Bacon/Augustine/Douglass/Newman packets remain in the repo as previous-sequence materials until Wayne decides whether to revise, renumber, archive, or replace them.

New packet built: `student-packets/02_homer_sirens_handout.tex` and `student-packets/02_homer_sirens_handout.pdf`.

## Bacon renumbered and revised as Reading 3

The next active packet is now Bacon's Four Idols as Reading 3, revised to follow Plato and Homer rather than Plato alone. The packet connects Bacon's idols both to the cave and to the Sirens as dangerous, knowledge-shaped attraction. Support materials were updated to mark Bacon complete in the revised sequence.

New active packet built: `student-packets/03_bacon_four_idols_handout.tex` and `student-packets/03_bacon_four_idols_handout.pdf`. The older `02_bacon_four_idols_handout.*` files remain as legacy copies from the previous sequence.
