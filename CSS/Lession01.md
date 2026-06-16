# CSS — Cascading Style Sheets

## Ways to Apply CSS

**1. Inline styling** — CSS is written directly inside an HTML tag using the `style` attribute. It applies only to that single element and has the highest priority among the three methods.

**2. Internal (style tag)** — CSS is written inside a `<style>` tag, placed in the `<head>` of the HTML file. It applies to the whole page that the HTML file represents, but only that one file.

**3. External (separate file)** — CSS is written in a completely separate `.css` file, then linked to the HTML file using a `<link>` tag. This is the most scalable method since one CSS file can be linked to multiple HTML pages, keeping styling consistent and code reusable.

## Selectors

CSS lets you target HTML elements in three main ways: by **tag name**, by **id**, or by **class**.

- **Tag selector** — targets all elements of a given tag type directly by name, no prefix needed. Affects every instance of that tag on the page.

- **ID selector** — starts with `#`. An id is meant to be unique, i.e., assigned to only one element on a page. Used when you want to style or target one specific element.

- **Class selector** — starts with `.`. Unlike id, a class can be reused on multiple elements, making it ideal for styling groups of elements the same way.

**Specificity note (worth remembering):** when rules conflict, inline styling overrides internal/external CSS, and id selectors override class selectors.
