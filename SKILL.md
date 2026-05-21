---
name: human-writing
description: "Rewrite or draft long-form prose (essays, articles, opinion pieces, sociological or critical writing, LinkedIn long-form posts, white papers, book chapters) so that it reads as written by a human, not assembled by an LLM. Use this skill whenever a text needs to escape the recognisable register of LLM output — symmetric structure, ring-around-the-rosie repetition, uniformly conciliatory tone, plausible-but-suspect bibliography, recurring connective formulas. Activate when the user asks to 'make it more human', 'less AI', 'less generated', 'less academic', 'with a real voice', 'più umano', 'meno LLM', 'meno generato', or when an LLM-classifier flagged the text. Activate also as a default for any essay or critical writing longer than ~500 words. Do NOT activate for chat replies, code, technical documentation, slide bullets, FAQ entries, or any text where structural regularity is a feature, not a bug."
---

# Human writing

This skill governs how to rewrite or draft long-form prose so that it reads as written, not generated. The reference failure mode is the prose described by stylometric critics of LLM output: didactically perfect structure, semantic ring-redundancy, isotropic tone, conciliatory argumentation, plausible-but-confabulated bibliography.

Works in Italian and English. Examples below are in both.

---

## When to use

**Activate for:**
- Essays, articles, opinion pieces, long-form LinkedIn posts
- Critical, sociological, philosophical or humanities writing
- Book reviews, exhibition reviews, journalistic features
- Rewrites of LLM-drafted text that needs to pass as human-authored
- Any prose longer than ~500 words where voice matters

**Do NOT activate for:**
- Chat replies and conversational answers
- Technical documentation, API docs, code comments
- Slide bullets, FAQ entries, product copy
- Short marketing copy where punchy regularity is a feature
- Translation work (use language-specific skills instead)
- Texts the user has already revised — those are final

---

## The diagnosis: what makes prose read as LLM-generated

LLM output, especially in essayistic register, tends to combine several recurring stylistic features. These features are not individually fatal — a careful human writer can produce any one of them — but their **co-occurrence at high density** is the signal.

### 1. Symmetric structure
- Introduction → taxonomy in points → theoretical framework → case study → conclusion → "further research"
- Every concept articulated in three nodes
- Sections of similar length, each with parallel substructure
- Every list a tripartition; every tripartition with balanced items

### 2. Recurring connective formulas
Watch for these phrases. Italian:

`in questo senso` · `dal punto di vista X` · `può essere interpretato come` · `non sostituisce X ma lo integra` · `funge da` · `in questo contesto` · `vale la pena sottolineare` · `è importante notare che` · `in altre parole` · `si potrebbe dire` · `lungi dall'essere` · `non solo X, ma anche Y`

English:

`in this sense` · `from an X perspective` · `can be interpreted as` · `serves as` · `it's worth noting` · `it's important to emphasize` · `not only X, but also Y` · `in this context` · `at its core` · `more than just` · `a testament to` · `delve into` · `navigate the complexities of`

Any one of these is fine. Three in the same paragraph is the LLM signature.

### 3. Semantic ring-redundancy
LLMs recycle the same handful of nuclear terms across the whole text. If your draft repeats the same key noun (`the rupture`, `the seal`, `the portal`) every paragraph with minor variation, you have it. A human writer names the concept once and lets the reader carry it forward.

### 4. Isotropic tone
- No shift in register across the piece
- No idiosyncratic word choices
- No hesitations, no asides, no "I'm not sure but"
- No moments of accelerated argument or deliberate slowing
- Even when criticising, conciliatory — every objection answered, every tension resolved

### 5. Conciliatory argumentation
- Integrates incompatible theoretical traditions without acknowledging incompatibility
- Beck and Bauman cohabit without friction; Marx and Hayek become "complementary perspectives"
- Every section ends with a synthesis
- No real disagreement with anyone, including the author

### 6. Plausible-but-confabulated bibliography
The single highest-value red flag. LLM-generated reference lists are:
- Topically perfect (every reference fits the argument too neatly)
- Formally plausible (real author, real-sounding publisher, real-sounding year)
- But the title is wrong, or the publisher is wrong, or the year is wrong, or the book doesn't exist
- Common pattern: real author + invented title + plausible publisher

Examples of typical confabulations:
- "Harvey, David. *Il brevetto del neoliberismo*" — Harvey's book is *Breve storia del neoliberismo*
- "Jenkins, Henry. *Texture of Culture*" — Jenkins wrote *Convergence Culture* and *Textual Poachers*; this title doesn't exist
- "Arrighi, Giovanni. *Il lungo Diciannovismo*" — the book is *Il lungo XX secolo*

---

## The treatment: techniques for humanising prose

### 1. Break structural symmetry
- Vary section length deliberately. Some sections four paragraphs, some one.
- Drop the obligatory "further research" / "future directions" closing.
- Use sub-headings unevenly: some sections numbered, some not, some untitled.
- Refuse the temptation to always tripartite. If the argument has two parts, two. If five, five.

### 2. Take positions
- First person where it earns its place: `I propose`, `I prefer a leaner formulation`, `mi pare`, `preferisco`
- Commit to a reading instead of presenting balanced alternatives the author will then "synthesise"
- Allow yourself to dismiss something: `the metaphor of the antenna is seductive, and for that reason suspect`
- State limits *as part of the argument*, not as a tacked-on disclaimer

### 3. Introduce real theoretical friction
- Invoke a theorist *and* indicate immediately what they don't explain
- Don't harmonise schools that are actually incompatible — name the incompatibility
- Leave tensions open. The reader can hold them.

### 4. Prefer concreteness to generality
- Specific dates, names, page numbers, titles
- Concrete examples instead of formulas: not `popular culture often X` but `Gea n. 14 does X`
- When you generalise, say so explicitly: `with prudence`, `roughly`, `as an approximation`

### 5. Vary sentence rhythm
- Long subordinate periods, then a short sentence. Then another.
- Allow nominal sentences. Fragments, sometimes.
- Use the em-dash for asides — but not as a default connector.
- Read aloud. If it sounds metronomic, it is.

### 6. Reduce repetition of key terms
- Name the central concept once. Then let pronouns, demonstratives or paraphrase carry it.
- Resist the urge to restate the thesis at the start of every section.
- The reader remembers what was said three paragraphs ago. Trust them.

### 7. Honest bibliography
- Verify every reference. Author, title, publisher, year.
- If you can't verify it, cut it.
- 10 verifiable sources beat 30 plausible ones.
- Flag uncertainty when it remains: `(edizione esatta da verificare)`.

---

## Banned phrases — quick reference

When rewriting, search the draft for these and replace or cut. The replacement is almost never another connective — it's restructuring the sentence so no connective is needed.

### Italian
- `in questo senso` → cut or restructure
- `dal punto di vista X` → state the claim directly
- `può essere interpretato come` → `è` / `funziona come` / restructure
- `non sostituisce X ma lo integra` → cut, find a more committed formulation
- `funge da` → `è` / specific verb
- `in questo contesto` → cut
- `vale la pena sottolineare` → cut, just say the thing
- `è importante notare che` → cut, just say the thing
- `lungi dall'essere` → restructure positively

### English
- `in this sense` → cut
- `it's worth noting that` → cut, just say it
- `serves as` → specific verb
- `at its core` → cut
- `more than just X, it's Y` → restructure
- `delve into` → `examine` / `look at` / `read`
- `navigate the complexities of` → just name what's complex
- `a testament to` → restructure

---

## Examples: before and after

### Example 1 (Italian, sociological essay)

**LLM draft:**
> Dal punto di vista sociologico, la struttura narrativa di Gea può essere interpretata come metafora del trauma collettivo della società del rischio. In questo senso, la rottura del sigillo funge da iconografia visiva del passaggio da un regime di sicurezza relativa a un regime di irreversibilità. In questo contesto, la cultura popolare non sostituisce la sociologia, ma la integra emotivamente.

**Human rewrite:**
> La rottura del sigillo è un'immagine forte e va trattata con cautela. Beck spiega una condizione strutturale; non spiega un'iconografia. Quello che si può dire — con prudenza — è che la serie e la teoria si parlano: condividono un campo problematico, l'irreversibilità, l'opacità delle cause. Non si spiegano a vicenda.

Notice what changed: three banned phrases gone, the conciliatory `non sostituisce ma integra` formulation replaced by a more committed `non si spiegano a vicenda`, an `I'm not sure` register introduced via `con prudenza`.

### Example 2 (English, opinion piece)

**LLM draft:**
> At its core, the platform serves as more than just a productivity tool — it's a testament to how AI can navigate the complexities of modern knowledge work. It's worth noting that the platform integrates seamlessly with existing workflows, augmenting rather than replacing human judgment.

**Human rewrite:**
> The platform is a productivity tool, and it's a better one than most. It works with the workflows people already have, and it doesn't pretend to replace the judgment calls that actually matter. That's all I want from this category of software.

Six banned phrases gone. Voice committed. Generalities replaced with a stated preference.

### Example 3 (Italian, LinkedIn long-form)

**LLM draft:**
> L'intelligenza artificiale generativa sta trasformando profondamente il modo in cui i designer lavorano. In questo senso, è importante notare che strumenti come Claude e Figma non sostituiscono la creatività umana, ma la integrano, fungendo da catalizzatori per nuove forme di esplorazione progettuale.

**Human rewrite:**
> Claude e Figma non sostituiscono la creatività di un designer. Cambiano il punto di partenza: meno tempo speso sulle prime varianti, più tempo sulla scelta. Il vero guadagno è qui, e non si vede nei demo.

Four banned phrases gone. First person implied. Concrete claim (`meno tempo sulle prime varianti, più tempo sulla scelta`) replaces an abstraction.

---

## Workflow

When asked to rewrite an LLM-flagged text:

1. **Read it whole.** Identify the actual thesis (often one sentence buried mid-text).
2. **Map the symmetry.** Mark sections that are structurally parallel — these are candidates for de-symmetrising.
3. **Scan for banned phrases.** Use the lists above. Mark every occurrence.
4. **Audit the bibliography.** For each reference, can you verify author + title + publisher + year? If not, cut.
5. **Rewrite section by section.** Don't rewrite sentence by sentence — that preserves the underlying structure. Rewrite by *paragraph*, holding the argument but reshaping its surface.
6. **Cut 20–30%.** LLM drafts are almost always overlong. The text gets stronger.
7. **Read aloud.** If the rhythm is metronomic, sentence-vary.
8. **Re-audit banned phrases.** They sneak back in during rewriting.

When asked to *draft* (not rewrite):

- Skip step 1.
- After drafting, apply steps 3–8.
- The first draft will fail the audit. That's normal. Two passes is the minimum.

---

## What this skill does NOT do

- **It does not guarantee that the text will pass an LLM-detection classifier.** Classifiers are noisy, prone to false positives on any structured prose, and update faster than this skill does. The goal is prose that reads as human to a human reader, not prose that defeats a detector.
- **It does not work on very short texts.** Below ~200 words there isn't enough surface for the patterns to register.
- **It does not replace a human revision pass.** The output is a stronger draft, not a finished product. The user should still read and tune.
- **It does not apply to all genres.** Technical documentation, legal text, FAQ entries, slide bullets — structural regularity is *a feature* there. Don't apply this skill where regularity is the point.
- **It does not invent voice from nothing.** If the text has no thesis, no position, no specificity, this skill can't manufacture them. It can only sharpen what is already there. When the underlying argument is empty, the rewrite reveals the emptiness — that is itself useful information.

---

## Reference

The diagnostic vocabulary (semantic ring-redundancy, isotropic tone, plausible-but-confabulated bibliography) comes from stylometric critiques of LLM output. The principles for humanising prose draw on the standard rhetorical tradition — variation of period length, committed voice, structural asymmetry — applied here specifically as countermeasures to identifiable LLM tics.

If a passage seems borderline, the test is simple: would a competent human writer, writing carefully and with a position, produce *this exact paragraph*? If the honest answer is "only if they were trying to sound neutral and exhaustive", the paragraph needs more work.
