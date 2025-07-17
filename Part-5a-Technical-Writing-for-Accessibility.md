
![Technical Writing](/images/technical-writing-1024x574.png "Technical Writing")


# ♿ Technical Writing for Accessibility

> Writing for accessibility ensures your documentation is inclusive and usable by **everyone**, including those with **permanent**, **temporary**, or **situational** disabilities. Great technical writing is not only clear — it's accessible.

---

## 📑 Table of Contents

1. [Why Accessibility Matters](#-why-accessibility-matters)
2. [Add Alt Text to All Images](#-add-alt-text-to-all-images)
3. [Use Sufficient Color Contrast](#-use-sufficient-color-contrast)
4. [Avoid Visual-Only Communication](#-avoid-visual-only-communication)
5. [Use a Proper Heading Structure](#-use-a-proper-heading-structure)
6. [Use Descriptive Link Text](#-use-descriptive-link-text)
7. [Use Clear and Simple Language](#-use-clear-and-simple-language)
8. [Practice Editing for Accessibility](#-practice-editing-for-accessibility)
9. [Resources](#-resources)
10. [Navigation](#navigation)

---

## ✅ Why Accessibility Matters

Accessible content allows:
- People with **visual impairments** to understand diagrams using screen readers.
- Users with **temporary injuries** (like a broken arm) to still navigate and consume documentation.
- People in **low-light or high-noise** environments to rely on clear, well-structured content.

---

## 📷 Add Alt Text to All Images

**Alt text** (alternative text) is used by screen readers to describe an image to visually impaired users.

### Best Practices:
- Write alt text that **summarizes the purpose** of the image, not just its appearance.
- Keep it **brief but informative**.
- If the image is decorative only, use an empty `alt=""` so screen readers can skip it.

```html
<img src="api-flow.png" alt="High-level API request-response flow between client and server">
````

---

## 🎨 Use Sufficient Color Contrast

Ensure your text has strong contrast against its background. People with **low vision** or **color blindness** may not be able to distinguish low-contrast content.

### Tools:

* [WebAIM Color Contrast Checker](https://webaim.org/resources/contrastchecker/)
* Use at least **4.5:1** contrast ratio for normal text.

---

## 👁️ Avoid Visual-Only Communication

Don’t rely solely on **color**, **bold**, or **shapes** to convey meaning.

✅ Do:

> “Click the green **Save** button with the checkmark.”

❌ Don’t:

> “Click the green button to continue.”

---

## 🧩 Use a Proper Heading Structure

Headings allow screen reader users to **navigate quickly**.

### Example:

```markdown
# Page Title
## Section Heading
### Subsection Heading
```

* Don't skip heading levels (e.g., from H2 to H4).
* Use headings semantically — not just for size.

---

## 🔗 Use Descriptive Link Text

Avoid vague links like:

> [Click here](#)

Instead, use:

> [Learn more about accessibility best practices](https://www.w3.org/WAI/)

This helps users using screen readers understand the **context and purpose** of the link.

---

## ✍️ Use Clear and Simple Language

Write for a **broad audience**:

* Avoid technical jargon unless your audience expects it.
* Keep sentences short and concise.
* Define complex terms the first time you use them.

---

## 🧪 Practice Editing for Accessibility

Before publishing, review content for:

* **Correct heading structure**
* **Proper alt text**
* **Good link labels**
* **Color contrast**
* **Plain language**

Use accessibility checkers or plugins in your writing tools to spot issues early.

---

## 📘 Resources

* [W3C Accessibility Guidelines](https://www.w3.org/WAI/)
* [Google's Accessibility Developer Docs](https://developers.google.com/web/fundamentals/accessibility)
* [Deque's Axe Accessibility Tools](https://www.deque.com/axe/)

---

## Navigation

<div style="display: flex; justify-content: space-between; width: 100%; max-width: 600px; margin-top: 30px;">

  <a href="Part-4-Error-message.md" style="text-decoration:none; background-color:#6c757d; color:white; padding:10px 20px; border-radius:5px; width: 120px; text-align: center;">
    ← Previous
  </a>

  <a href="README.md" style="text-decoration:none; background-color:#007bff; color:white; padding:10px 20px; border-radius:5px; width: 120px; text-align: center;">
    Home →
  </a>

</div>


---

