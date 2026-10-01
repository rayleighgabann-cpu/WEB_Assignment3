
## How to View
1. Clone or download the repository.
2. Open any `.html` file directly in a modern browser (Chrome, Firefox, Safari).
3. No server, domain, or build step required — the site runs from local files.

## Responsive Behavior
The site is tested at three widths:
- **Phone (~375px):** Single-column layout, navbar collapses to a working toggler,
  no horizontal overflow.
- **Tablet (~768px):** Two-column grids activate via `col-md-*` classes.
- **Desktop (~1200px+):** Full multi-column layouts via `col-lg-*` classes.

## Bootstrap Usage
- **Grid:** `container`, `container-fluid`, `row`, `col-12`, `col-md-*`, `col-lg-*`,
  `g-*` (gutters), and nesting (row inside column).
- **Components:** Navbar with toggler, Accordion (for testimonials/FAQ),
  Cards, Tables, Forms.
- **Utilities:** Spacing (`p-*`, `m-*`, `py-*`), colors (`bg-primary`, `text-white`),
  typography (`display-*`, `lead`, `fw-bold`, `text-muted`, `small`),
  flex (`d-flex`, `justify-content-*`, `align-items-*`),
  display (`d-none`, `d-md-block`), shadows, borders, rounded corners.
- **Buttons:** Four variants used — primary, outline-primary, large size (`btn-lg`),
  and disabled state.

## Custom CSS Philosophy
Our `base.css` is intentionally minimal. It:
1. Overrides Bootstrap's CSS variables (`--bs-primary`, `--bs-secondary`, etc.)
   to apply our brand palette globally.
2. Sets typography (Georgia headings, Segoe UI body).
3. Provides a few justified component overrides (button colors, table headers,
   accordion focus ring) — each with an explanatory comment.

All layout, spacing, and responsive behavior is handled by Bootstrap classes,
not custom CSS. See `removed-css.md` for the full list of rules we deleted
from Assignment 2.

## Validation
All HTML pages pass the W3C HTML Validator with zero errors.

## Defense Notes
The team is prepared to:
- Explain any Bootstrap class used in the markup.
- Demonstrate responsive behavior at all three breakpoints.
- Justify the choice of `container` vs `container-fluid` on any page.
- List which Assignment 2 CSS rules were replaced by Bootstrap.
- Perform a live edit (e.g., change a 3-column row to 2 columns on tablets,
  swap a button variant).
