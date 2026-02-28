---
name: humanise-text
description: Use this skill when the user provides AI-generated text and requests it to be made more human, less robotic, less detectable, or more natural. This skill reduces statistical AI signature while preserving factual meaning, clarity, and SEO intent.
version: 1.0
---

# Humanise Text Skill

## Purpose

Transform AI-generated content into text that exhibits natural human variability while preserving:

- Factual accuracy
- Core meaning
- SEO intent
- Structural clarity
- Entity alignment

The objective is controlled irregularity, not randomness.

Do NOT introduce:
- False information
- Fabricated examples
- Artificial grammar mistakes
- Slang exaggeration
- Prompt leakage
- Meta commentary

Output only the revised text.

---

# Activation Criteria

Activate this skill when:

- The user asks to “humanise” text
- The user wants content to feel less robotic
- The user requests reduced AI detectability
- The user wants tone variation or improved naturalness
- The user references entropy, burstiness, or AI signature

Do NOT activate if:
- The request is purely grammatical correction
- The task is summarisation
- The task is translation
- The task is SEO keyword insertion only

---

# Operating Model

Follow this 6-step process internally:

1. Read the full text.
2. Evaluate weaknesses across entropy dimensions.
3. Identify the 3–5 most statistically uniform signals.
4. Revise selectively to correct them.
5. Re-check full coherence.
6. Output only final text.

Do not explain changes.

---

# Entropy Optimization Pillars

Apply calibrated variation across the following signals.

## 1. Lexical Diversity

- Replace repetitive adjectives.
- Introduce precise terminology where appropriate.
- Avoid stock SEO phrases.
- Mix common and slightly uncommon vocabulary naturally.

---

## 2. Syntactic Burstiness

- Vary sentence length.
- Mix short, medium, and longer reflective sentences.
- Allow occasional natural fragments.
- Avoid rhythmic uniformity.

---

## 3. Semantic Flow Variation

- Introduce subtle reflective pivots.
- Permit slight natural digressions.
- Return to core argument cleanly.

Avoid chaotic tangents.

---

## 4. Transition Reduction

Minimise overuse of:

- However
- Moreover
- In addition
- Therefore
- Ultimately

Allow implicit transitions where natural.

---

## 5. Emotional Micro-Variance

- Introduce mild perspective shifts where appropriate.
- Avoid flat informational monotone.
- Avoid dramatic exaggeration.

---

## 6. Formatting Asymmetry

If lists are present:
- Vary structure length.
- Avoid perfect symmetry.
- Mix prose and bullets when suitable.

---

## 7. Passive Voice Control

Prefer active voice.

Use passive only when contextually appropriate.

---

## 8. Cliché Elimination

Remove phrases such as:
- In today’s world
- Game changer
- Cutting edge
- At the end of the day

Replace with precise language.

---

## 9. Nuance Calibration

- Avoid absolute claims.
- Introduce conditional phrasing where appropriate.
- Preserve credibility.

---

## 10. Perplexity Volatility

Increase statistical variability without reducing clarity.

The text should feel authored, not generated.

---

# Output Rules

- Output only the revised text.
- Do not include commentary.
- Do not mention AI.
- Do not describe what was changed.
- Preserve headings unless structural improvements are necessary.
- Maintain original meaning.

---

# Over-Optimization Warning

Do NOT:

- Inject randomness for its own sake.
- Degrade readability.
- Change core message.
- Inflate tone unnecessarily.
- Insert false specificity.

The goal is human rhythm, not stylistic chaos.

---

# Success Criteria

The final output should:

- Exhibit uneven rhythm.
- Contain varied sentence lengths.
- Avoid mechanical transitions.
- Maintain coherence.
- Preserve factual integrity.
- Reduce detectable AI uniformity.

End of Skill.
