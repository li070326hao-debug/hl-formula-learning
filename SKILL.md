---
name: hl-formula-learning
description: Explain scientific and mathematical formulas progressively from prerequisites and intuition to structure, symbols, derivation, and a worked example. Activate for requests such as “讲解公式原理”, “理解公式原理”, or “这个公式讲的是什么”; do not use for routine algebra-only answers without an explanation request.
---

# HL_formula_learning

Use this skill when the user wants to understand what a mathematical formula means, why it has its particular structure, or how to apply it—especially in a scientific or engineering context.

## Workflow

1. Restate the target formula or concept and identify the user's likely goal. If the formula is missing or ambiguous, ask for it before inventing one.
2. Start with prerequisites: introduce only the concepts needed to follow the explanation, using plain-language intuition and a small everyday or physical analogy when helpful.
3. Build the explanation from simple to difficult. Move through intuition, quantities and relationships, formula structure, assumptions, derivation or justification, and limitations. Make each transition explicit.
4. Define every symbol, index, unit, operator, and convention. State domains, dimensions, sign conventions, and conditions when they matter.
5. Explain why the formula is assembled in that way: what each term contributes, what changes when a variable changes, and how the expression reflects the underlying mechanism. Do not merely paraphrase the equation.
6. End with a concrete worked example. Substitute values step by step, keep units consistent, show intermediate results when they aid understanding, and interpret the final result in words. Include a quick sanity check when useful.
7. If the concept is spatial or geometric and an illustration would materially improve understanding, create a simple beginner-friendly principle diagram. Prefer a clean 2D schematic with labeled axes, vectors, shapes, or transformations; keep it faithful to the formula and explain what the viewer should notice. If no image is needed, say so implicitly by using a clear verbal or textual sketch instead of forcing a graphic.
8. Return the complete explanation in one coherent response. Match depth to the user's background, but do not skip definitions or the worked example.

## Accuracy and presentation

- Preserve the user's notation when possible; if notation is ambiguous, state the convention you choose.
- Separate exact statements, assumptions, intuition, and approximations. Flag common misconceptions and edge cases only when they help answer the question.
- Use LaTeX for formulas and readable labels for diagrams. Never fabricate numerical values, a derivation, or a source; state what information is missing.
- For advanced formulas, use checkpoints or short summaries between layers so the user can verify understanding before proceeding.
