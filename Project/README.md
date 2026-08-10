# Milestone 2 Project Requirements

## 1. Accessibility Fixes (WAVE)
- **Empty Link Fix:** Checked for the empty link flagged by WAVE and verified that all anchor tags contain descriptive text instead of remaining empty.
*Note: Checked all text/background color combinations with WebAIM Contrast Checker and they pass WCAG AA contrast standards.*

## 2. Visual Design & Gestalt Principles
- **Proximity:** I used proximity in the contact form to visually group form labels closely with their corresponding input fields, making it immediately clear which label belongs to which input.
- **Similarity:** I used similarity by applying consistent vivid pink accents (`#FF2E93`) and hover effects to all interactive elements (buttons, links, form focus states) across the site to clearly signal they are actionable. My color palette is consistent across all pages.

## 3. Accessible Form
I added an accessible contact form to the `about.html` page. It includes:
- Semantic `<label>` elements explicitly associated with inputs via the `for` attribute.
- A `<fieldset>` and `<legend>` to group the form logically.
- Accessible error states and required attributes (`aria-required="true"`, `aria-invalid`).
