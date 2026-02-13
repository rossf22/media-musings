# Media Musings

These are the starter files for a multi-part Responsive Web Design assignment. You’ll focus on **layout + visual design**, and then you’ll adapt the same design for **tablet and phone** in later steps.

## What this assignment is (the big picture)

- **Part 1 — Desktop layout only**
  - Build a polished desktop design.
  - **Do not add media queries yet.**
- **Part 2 — Fix + refine**
  - After you submit the assignment, the walkthrough video will unlock
  - Watch the walkthrough video to see how everything should have been done and fix your code
- **Part 3 — Responsive**
  - Next week you'll have an assignment to revisit this site and add media queries to adjust the layout for tablets and phones.

> **Important:** The full checklist of required styles and layout rules is in the Canvas assignment description.

---

## What you should edit

You will primarily edit:

- `css/main.css`

The HTML is already built for you. You are **not** expected to rewrite the HTML structure. Instead, your job is to:

- read the existing structure
- use the provided CSS comments
- apply CSS to the correct selectors

---

## How to avoid getting lost

Most people struggle on this project when they jump around randomly in the CSS.

Work in this order:

1. **Big layout first** (page wrapper, header, main grid)
2. **Place the major sections** (blog article, asides, campus grid)
3. **Then polish** (fonts, colors, spacing, shadows, hover effects)

If you do small details first (colors, fonts, hover effects) before the layout is working, it usually feels confusing fast.

---

## Publishing (GitHub Pages)

You will publish your site using **GitHub Pages** and add your live URL to the **About** section of your repository.

Canvas has the exact steps.

---

## New semantic elements in this project: `<article>` and `<aside>`

In this starter code, you’ll see two new HTML elements being used for the first time: `<article>` and `<aside>`.

These are **semantic HTML elements**, meaning they describe the *role* of the content (what it is) rather than how it looks.

You still control layout and appearance with **CSS**. Semantic elements are about **structure and meaning**.

---

### `<article>` — the main content

The `<article>` element is used for **self-contained, primary content** that could stand on its own.

In Media Musings, the written blog post is wrapped in an `<article>` because it is the main focus of the page.

Good candidates for `<article>` include:

- Blog posts
- News stories
- Opinion pieces
- Standalone entries or posts

**Rule of thumb:**  
If it would still make sense if it were shared or published by itself, it belongs in an `<article>`.

---

### `<aside>` — supporting / sidebar content

The `<aside>` element is used for **supporting or related content** that is not essential to the main article.

In this project, there are **two** `<aside>` sections:

- **Recent Articles**
- **Links**

These are sidebar-style blocks that support the page, but the page would still work without them.

Good candidates for `<aside>` include:

- Related links
- Lists of recent posts
- Notes, commentary, or extra context
- Author info or small “sidebar” features

**Rule of thumb:**  
If it adds extra information, but the main content still works without it, it belongs in an `<aside>`.

---

### Why we’re using semantic HTML

Using semantic elements like `<article>` and `<aside>` instead of generic `<div>` elements helps:

- **Accessibility:** screen readers can understand page structure more clearly
- **SEO:** search engines can identify main vs. secondary content
- **Readability:** your HTML is easier to understand and maintain
- **Professional practice:** this is how modern real-world sites are structured

This project is a step toward building pages that are structured the way modern websites are built.
