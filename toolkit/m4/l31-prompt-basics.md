# Lesson 31 of 49 – Prompting Basics

> **Overview**: Effective prompting hinges on three building blocks—Task, Context, and Output Format. Mastering each ensures the generative AI understands *what* to do, *why* it matters, and *how* to present the answer.

## Core Building Blocks

- **Task** – A concise, verb‑driven statement that defines the desired outcome.
  *Key ideas*: start with an action verb (Define, Create, Research, Find, Synthesize, Explain, Translate, Convert); be specific; avoid vague phrasing.

- **Context** – Background information that equips the model with the necessary knowledge to fulfil the task.
  *Key ideas*: include relevant data, examples, personas, tone; keep it succinct yet sufficient.

- **Output Format** – Explicit instruction on how the answer should be structured.
  *Key ideas*: specify format types such as tables, bullet lists, emails, surveys, length constraints, or any custom layout.

## Practical Prompt Example

```markdown
Task: Create a three‑column table summarizing the main AI ethics principles.
Context: Use the IEEE “Ethically Aligned Design” document (2020 edition).
Output Format: Markdown table with columns “Principle”, “Description”, “Reference URL”.
```

## Checklist for Prompt Review

- [ ] Verify the task starts with a clear verb and is specific.
- [ ] Ensure the context provides all necessary background without overload.
- [ ] Confirm the output format matches the intended consumption medium.
- [ ] Request source citations from the model to validate information.

---

*Always evaluate the AI's response for accuracy, bias, and relevance before using it in production.*

