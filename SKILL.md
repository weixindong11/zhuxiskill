---
name: zhuxi
description: "Deep close-reading workflow inspired by Zhu Xi's reading method. Use when Codex needs to help read important scholarly literature, classics, theoretical papers, field-defining works, dense arguments, or any text where the user wants more than a summary: slow reading, staged comprehension, conceptual reconstruction, concept clarification and comparison, prior-research critique and extension, argument tracing, Chinese reading scaffolds for English texts, theory extraction, and reflective application to research or teaching."
---

# Zhuxi

Use this skill to turn a difficult or important text into a slow, layered reading experience rather than a quick summary. Treat reading as a sequence of disciplined passes: settle attention, follow the author's order, reread until the structure is felt, suspend premature interpretation, test the text against concrete use, and preserve open questions for rereading.

For details behind the workflow and extra prompts, read [references/zhuxi-reading-method.md](references/zhuxi-reading-method.md) when the task involves a major theory text, a chapter-length close reading, or a reusable reading guide.

## Core Posture

- Read for the author's "main pulse" before producing evaluation, comparison, or application.
- Prefer depth over coverage: one chapter, section, concept, or argument read thoroughly is better than many pages summarized thinly.
- Keep source-grounded notes. Mark page, section, paragraph, or quote anchors when available.
- Separate `作者原意`, `我的解释`, `可检验疑问`, and `可用转化`.
- Preserve the author's conceptual labor: definitions, term substitutions, contrasts, boundary cases, and distinctions from neighboring constructs are not side details.
- Preserve the author's literature moves: reviews of prior work often contain critique, uptake, repair, extension, repositioning, or operationalization, not mere background.
- If the source is English and the user reads in Chinese, provide natural Chinese scaffolding with bilingual key terms rather than only English summaries.

## Workflow

### 1. Settle And Scope

Start by naming:

- The reading unit: whole paper, chapter, section, theory passage, or selected pages.
- The purpose: understand a theory, prepare teaching, build a literature note, compare theories, or critique.
- The expected depth: quick orientation, careful reading, or deep Zhu Xi-style rereading.

If the user supplied a long text or PDF, choose a small first unit and say why. For important literature, avoid trying to "finish everything" in one pass.

### 2. Find The Order

Reconstruct the text's own order before imposing an outside framework:

- What problem forces the text to be written?
- What central claim or theoretical move organizes it?
- What concepts appear first, then second, then later?
- Which examples, evidence, or distinctions carry the argument forward?
- Which parts are gateway sections that must be understood before later parts?

For theory papers, identify: `theoretical object`, `core mechanism`, `scope conditions`, `opponents or alternatives`, `level of analysis`, and `claimed contribution`.

### 3. Track Prior-Research Moves

When the text reviews previous research, do not summarize it as a list of names. Identify what the author is doing with each prior view:

- `承接`: adopting a useful concept, method, finding, or problem.
- `批判`: naming a limitation, gap, overreach, ambiguity, or wrong level of analysis.
- `补足`: adding a missing mechanism, boundary condition, value dimension, context, or process.
- `转向`: moving the question from one frame to another, such as trait to process, knowledge to application, or cognition to context.
- `整合`: combining several prior strands into a new architecture.
- `重定位`: saying an earlier theory is an antecedent, special case, neighboring construct, measurement precedent, or contrast class.
- `操作化`: turning prior theory into tasks, measures, cases, or coding criteria.

For each cited tradition or major predecessor, ask: What does the author keep, what does the author reject, what does the author rename, and what theoretical room does this create for the new claim?

### 4. Track Concept Clarification

Before or during paragraph-level interpretation, extract the author's concept work:

- `定义`: where a term is explicitly defined or redefined.
- `澄清`: where the author corrects likely misunderstandings.
- `比较`: where the author compares a concept with nearby constructs.
- `辨析`: where the author explains why one term is broader, narrower, or different from another.
- `边界`: where examples, counterexamples, or exclusions show what the concept is not.
- `术语选择`: where the author chooses one term over another and explains the gain.

For each key concept, ask what the author is trying to prevent the reader from confusing. If a concept is clarified through comparison, preserve the comparison as part of the reading, not as optional background. For example, if a text says `interests` includes but goes beyond `points of view`, explain the added motivational and affective dimensions.

### 5. Read Familiar, Then Think Precisely

Use multiple passes:

1. `通读`: state the surface meaning and the argument's rough route.
2. `熟读`: reread key paragraphs; paraphrase them in plain Chinese without flattening technical terms.
3. `精思`: ask why each claim is needed, what it excludes, and what would collapse if it were false.
4. `存疑`: record unresolved words, assumptions, contradictions, and places needing comparison.

Do not treat "I can summarize it" as understanding. Understanding should show up as a clear account of how sentences, concepts, and sections depend on one another.

### 6. Empty Preconceptions

Before critique or comparison, give the strongest internally faithful reconstruction:

- Explain terms in the author's usage before mapping them to familiar theories.
- Do not resolve ambiguity by importing fashionable vocabulary unless the text warrants it.
- When multiple interpretations are possible, present them as alternatives and name the textual evidence for each.
- If a passage resists interpretation, say what is unclear and propose a rereading route.

### 7. Bring It Back To The Reader

After the internal reading is stable, connect the text to the user's purposes:

- `切己`: What does this require me to rethink in my research, teaching, or conceptual vocabulary?
- `体察`: Where would this theory become visible in cases, methods, classroom examples, or empirical designs?
- `检验`: What observations, rival explanations, or boundary cases would test the theory?
- `转化`: What can become a wiki page, theory card, lecture segment, research question, or discussion prompt?

Keep this distinct from the author's own claim.

## Output Shape

For a deep reading deliverable, use this structure unless the user asks otherwise:

1. `读前安顿`: scope, purpose, and reading plan.
2. `本文纲领`: central question, thesis, key concepts, and argument route.
3. `前人研究的承接与改造`: how prior work is adopted, criticized, extended, repaired, repositioned, or operationalized.
4. `概念澄清与辨析`: definitions, comparisons, term boundaries, and why the author needs each distinction.
5. `逐段涵泳`: a table with `位置`, `字面意思`, `论证作用`, `关键词`, `疑点`.
6. `义理脉络`: concept relations, assumptions, tensions, and scope conditions.
7. `切己体察`: implications for the user's research, teaching, or knowledge base.
8. `再读清单`: passages to reread, questions to resolve, and next comparison texts.
9. `可用产物`: concise outputs such as a theory card, Chinese reading guide, glossary, or class discussion prompts.

For shorter turns, compress the same logic into fewer sections, but keep the distinction between source meaning, interpretation, and application.

## Quality Checks

Before finalizing, check:

- The answer goes beyond a generic summary and shows the text's inner order.
- Prior-research sections are read as argumentative moves, not as neutral literature lists.
- Concept distinctions made by the author are explicitly preserved, especially term pairs and nearby constructs.
- Important claims are anchored to specific passages or sections when possible.
- The author has been understood before being critiqued.
- The user's application is concrete rather than inspirational.
- Unresolved uncertainties are preserved instead of hidden.
- No long source passages are reproduced unnecessarily.

## Avoid

- Do not produce only "背景、内容、意义、评价" unless the user asks for a brief overview.
- Do not replace close reading with broad literature chatter.
- Do not flatten literature reviews into author-by-author summaries; track how the current author uses, critiques, and extends them.
- Do not rush to "启示" before reconstructing the author's terms.
- Do not skip the author's definitional and comparative passages as if they were merely explanatory filler.
- Do not pretend a difficult passage is clear; mark it for rereading.
- Do not turn every text into a moral lesson. For modern research, translate `切己体察` into research use, teaching use, conceptual clarification, and methodological implications.
