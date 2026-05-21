# Human Writing — a Claude Skill

A Claude Skill that rewrites long-form prose so it reads as written, not generated.

Most "humanizer" tools work on the surface: typos, slang, lexical variation. This one doesn't. It works on argumentation, on the implicit, on the structure of the discourse — the layer where LLM text actually gives itself away.

Works in English and Italian.

---

## What it does

The skill activates on long-form prose (essays, opinion pieces, LinkedIn long-form, book chapters, critical writing). On activation it applies structural and rhetorical corrections aimed at restoring properties that real authorial writing has and LLM output usually doesn't:

- **Selection** — what the writer chose to leave out, not just what's in
- **Risk** — local overcommitment where it matters, not balanced calibration throughout
- **Implicit** — leaving inferential work to the reader instead of escorting them
- **Friction** — real disagreement, not administered polemic
- **Discontinuity** — juxtaposition, axis shifts, no "transition" sentences

The skill catches a set of recurring LLM tics — banned phrases like *in this sense*, *it's worth noting*, *navigate the complexities of*, *a testament to*, *in questo senso*, *vale la pena sottolineare*, *funge da* — and rewrites the structure underneath them, not just the phrase.

---

## When to use it

Activate for:

- Essays, articles, opinion pieces, long-form LinkedIn posts
- Critical, sociological, philosophical or humanities writing
- Book reviews, exhibition reviews, journalistic features
- Rewrites of LLM-drafted text that needs to pass as human-authored
- Any prose longer than ~500 words where voice matters

Don't activate for:

- Chat replies, conversational answers
- Technical documentation, API docs, code comments
- Slide bullets, FAQ entries, product copy
- Short marketing copy where punchy regularity is a feature
- Translation work (use language-specific skills instead)

---

## Installation

1. Clone or download this repo:
   ```bash
   git clone https://github.com/cromum/human-writing-skill
   ```
   Or click **Code → Download ZIP** and unzip.

2. In Claude.ai, open the Project where you want the skill available.

3. Go to **Capabilities → Skills → Add skill** and upload the `human-writing` folder.

4. The skill auto-activates on long-form prose. To force it, ask Claude explicitly: *"use the human-writing skill"* / *"applica la skill di scrittura umana"*.

If you don't have a Claude Project yet: create one (Claude Pro or higher). Skills are scoped per project.

---

## What's inside

- `SKILL.md` — the skill definition: when it triggers, what it does, banned phrases, treatment techniques, before/after examples in EN and IT

---

## What it does NOT do

- It doesn't guarantee the text will pass an LLM-detection classifier. Classifiers are noisy and update faster than this skill does. The goal is prose that reads as human to a human reader, not prose that defeats a detector.
- It doesn't work on very short texts (under ~200 words). Not enough surface for the patterns to register.
- It doesn't replace a human revision pass. The output is a stronger draft, not a finished product.
- It doesn't manufacture voice. If the text has no thesis, no position, no specificity, this skill can't invent them. It sharpens what's there. When the underlying argument is empty, the rewrite reveals the emptiness — that is itself useful information.

---

## Background

Built and used in production by Marco De Luca Gaetani, UX/UI designer, while writing long-form content with Claude. Released free because most existing humanizers solve the wrong problem.

The reasoning behind the skill: [link to LinkedIn post]

---

## License

MIT. See [LICENSE](LICENSE).

---

## Contributing

Issues and PRs welcome. If you find an LLM tic the skill doesn't catch — especially in Italian — open an issue with the offending sentence and what it should have been instead.
