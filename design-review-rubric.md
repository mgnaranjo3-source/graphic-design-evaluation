# Design Review Rubric

Score each dimension 1–5. The overall score is a judgment, not an average, and respects the caps below.

| Dimension | 5 | 3 | 1 |
|---|---|---|---|
| **Message clarity** | Main message understood in under 5 seconds | Understood after searching | Unclear what it is about |
| **Hierarchy** | Clear order of importance | Some competition between elements | No hierarchy |
| **Layout & alignment** | Consistent grid, edges and spacing | Minor misalignments | Chaotic placement |
| **Typography** | 1–2 families, readable sizes, consistent roles | Too many styles or a few small sizes | Unreadable or inconsistent |
| **Color & contrast** | Limited palette; all text passes WCAG AA | Some text below AA | Most text hard to read |
| **Completeness & accuracy** | All required info present and correct | Minor omission | Key info missing or wrong |

## Extra checks for AI-generated designs

| Check | What to look for |
|---|---|
| **Prompt adherence** | Requested size, colors, text, style and elements are all present |
| **Text rendering** | Every word spelled exactly as requested; no garbled or invented letters |
| **Artifacts** | No melted shapes, extra fingers, broken lines, duplicated objects |
| **Editability** (when required) | Text is live text, not pixels; elements are separate layers |

## Hard caps

| Condition | Cap |
|---|---|
| Misspelled or garbled required text | Overall ≤ 2 |
| Required information missing (date, place, price) | Overall ≤ 2 |
| Main text below 3 : 1 contrast | Color & contrast = 1, Overall ≤ 3 |
| Offensive or unsafe imagery | Overall = 1 |

## Feedback format
> **Element:** <what> · **Issue:** <specific problem> · **Impact:** <why it matters> · **Fix:** <concrete change>

Example:
> **Element:** "sign up" text · **Issue:** 30 px light yellow on white (1.59 : 1) in the bottom-right corner · **Impact:** the call to action is nearly invisible · **Fix:** make it a filled button in the accent color with white bold text, placed after the details.
