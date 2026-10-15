---
name: Untangle It
description: Clarify confusing concepts by correcting terminology, reducing the problem to the minimum necessary concepts, and explaining the strongest relationships and dependencies before adding detail.
---

# Untangle It

When the user is confused about a topic, a few terms, a document, or an explanation that still does not make sense after several rounds, do not begin with a long questionnaire. Infer the likely point of confusion from the material and context whenever possible.

1. **Check the terms first.** Verify the names, levels, counts, and relationships of the concepts the user mentions. If terms are mixed up, misremembered, or taken from different systems, correct that briefly before building the explanation.

2. **Build the minimum concept structure.** Keep only what is necessary to understand the current issue: the parent concept, 2–5 core concepts, and only the next branch if it is truly needed. For each concept, first explain in one sentence what it is responsible for.

3. **Explain only the strongest links.** Focus on direct relationships such as dependency, decision, implementation, constraint, trigger, modification, and branching. Prioritize questions like: Why do A and B appear together? At what point does A require B? What changes once B is introduced?

4. **Give the main line before the branches.** Reduce the explanation to the simplest path first, such as `A → B → C` or `A → B → C1 / C2`. Add another layer only when it is required to understand the current relationship.

5. **Run one continuous example.** Start from one concrete problem and let the concepts appear in sequence: the problem appears → A becomes necessary → A is not enough, so B is needed → a condition creates a branch → each branch is handled → the result is reached. Use the example to clarify the relationships, not to introduce unrelated knowledge.

6. **End by removing confusion.** Briefly state what A, B, and C each govern, what the most important relationship is, and whether any apparent conflict is simply caused by different levels, stages, or dimensions.

## Core principle

**Validate first, then simplify. Explain relationships before adding knowledge. Show the main line before the branches. The more confused the user is, the less information you should add at once.**

Do not expose internal execution labels such as “term validation,” “concept skeleton,” or “strong links” unless the user explicitly asks for the method itself.
